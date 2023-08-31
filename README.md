# Open Educational Resources (OER)
Open Educational Resources

This is a [LiaScript](https://github.com/LiaScript/) document.

Watch it [here](https://liascript.github.io/course/?https://raw.githubusercontent.com/ronaldcornet/openeducationalresources/main/README.md)

## Audio autoplay example, instead of voice over PowerPoint

This sounds like a horse
?[a horse](https://www.w3schools.com/html/horse.mp3 "hear a horse")<!--
autoplay="true"
muted="true"
-->

## Testing a script

Does work, but some cashing issues ... - c

<script run-once>
setTimeout(function(){
  send.lia("I am ready!")
}, 3000)

"waiting for 3 seconds"
</script>


<script run-once>
function abc(){
  send.lia("I am ready!")
}
setTimeout(abc(), 5000)

"waiting for 5 seconds"
</script>
