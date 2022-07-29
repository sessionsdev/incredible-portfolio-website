


<div class="">
<pre>
<code class="is-size-7">
fun main(args : Array{'<'}String{'>'}) {`{`}          
  println("Building better <span id="typewriter"/>")
{`}`}
</code>
</pre>
</div>

  <script>
      import Typewriter from 'typewriter-effect/dist/core';
      import { onMount } from 'svelte'

      onMount(() => {
        new Typewriter('#typewriter', {
        strings: ['integrations', 'servers', 'web apps'],
        autoStart: true,
        loop: true,
        });
      })
      

    
  </script>

  <style>
      pre {
        border-color: white;
        border-style: solid;
        background: black;
        color: white;
        padding-bottom: 0;
        overflow: hidden;
        box-shadow: 0 5px 25px 10px rgba(0, 0, 0, .25);
      }
/* 
      pre:hover {
        transform: scale(1.1);
        box-shadow: 0 15px 80px rgba(0, 0, 0, .25);
      } */

      code {
        font-family: monospace;
      }
  </style>