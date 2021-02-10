## Inline code blocks and comments

In this project, you will use <code class="blocks" style="background-color: white">say [Hello!] for (2) seconds</code> to make your sprite show a speech bubble.


<code class="blocks" style="background-color: white">when flag clicked</code><code class="blocks" style="background-color: white">forever</code><code class="blocks" style="background-color: white">point towards (mouse-pointer v)</code><code class="blocks" style="background-color: white">if on edge, bounce</code><code class="blocks" style="background-color: white">say [Hello!] for (2) seconds</code>

```blocks3
when this sprite clicked
think [Hmm...] // thought bubble
change [color v] effect by [100] // number up to 200
wait [1] secs
think [] // hide bubble
clear graphic effects // back to normal colour
```

A really long comment:
```blocks3
change [color v] effect by [100] // number up to 200 number up to 200 number up to 200 number up to 200 number up to 200
```

<code class="blocks" style="background-color: white">when flag clicked</code><code class="blocks" style="background-color: white">forever // inline comment</code><code class="blocks" style="background-color: white">point towards (mouse-pointer v)</code>

<script>
scratchblocks.renderMatching("code.blocks", {
  inline: true,
  style:     'scratch3',   // Optional, defaults to 'scratch2'.
  // Repeat `style` and `languages` options here.
});
</script>
