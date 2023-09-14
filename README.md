# Open Educational Resources (OER)
Open Educational Resources

This is a [LiaScript](https://github.com/LiaScript/) document.

Watch it <a href="https://liascript.github.io/course/?https://raw.githubusercontent.com/ronaldcornet/openeducationalresources/main/README.md" target="_blank">rendered</a> or <a href="https://raw.githubusercontent.com/ronaldcornet/openeducationalresources/main/README.md" target="_blank">raw</a>.

## Audio autoplay example, instead of voice over PowerPoint

This sounds like a horse
?[a horse](https://www.w3schools.com/html/horse.mp3 "hear a horse")<!--
autoplay="true"
muted="true"
-->

## Testing a script

Does work, but some caching issues ... - a

See [LiaScript ](https://github.com/LiaScript/docs/blob/master/README.md)

<script run-once>
setTimeout(function(){
  send.lia("I am ready!")
}, 3000)

"waiting for 3 seconds"
</script>

<script run-once>
function counter(i) {
  if (i > 0) {
    send.output("HTML: <h"+i+" style='display: inline-block'>hallo " + i +"</h"+i+">")
    setTimeout(() => counter(i-1), 1000)
  } else {
    send.stop()
  }
}

counter(6)

send.wait() // or "LIA: wait"
</script>

## An SVG, even animated!
![Example](https://dev.w3.org/SVG/tools/svgweb/samples/svg-files/anim3.svg)

![Open Educational Resources logo](https://upload.wikimedia.org/wikipedia/commons/2/20/Global_Open_Educational_Resources_Logo.svg)
