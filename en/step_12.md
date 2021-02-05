## What next?

In this project, you have:

+ applied your skills to realise your own project ideas to create an interactive animation
+ selected appropriate blocks for your plan
+ think about what you've made and the ways you can improve it

If you are following the [Look after yourself](https://projects.raspberrypi.org/en/raspberrypi/look-after-yourself) pathway and have not completed the last three projects - Fruit salad, Relax and stretch and Focus on the prize - then now continue the pathway with [Fruit salad](https://learning-admin.raspberrypi.org/en/projects/fruit-salad).

If you have completed all the projects in the [Look after yourself](https://projects.raspberrypi.org/en/pathways/look-after-yourself) pathway then move on to the next Challenge project, [Project name](https://projects.raspberrypi.org/en/projects/project-name) project. In this project, you will make an interactive animation using `variables`{:class="block3variables"}.


<code class="blocks">when flag clicked</code><code class="blocks">forever</code>

```blocks3
when flag clicked
set rotation style [left-right v] // Stop the butterfly going upside down when moving left
forever
point towards (mouse-pointer v) // Point towards the mouse or where you touch the tablet screen
move [3] steps // Move 3 steps towards the mouse pointer
if on edge, bounce // If the sprite is touching the edge, point in the opposite direction to keep the butterfly fully on the Stage.
end
```
<script>
scratchblocks.renderMatching("code.blocks", {
  inline: true,
  // Repeat `style` and `languages` options here.
});
</script>
