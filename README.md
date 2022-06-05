<html>
  <head>
    <title>&nbsp;</title>
    <script>
      // function for the day
      function light(n=500) {
        document.body.innerHTML="";
        document.body.style.background="#444";
        h=window.innerHeight;
        w=window.innerWidth;
        for(i=0;i<n;++i){
          d=document.createElement('span');
          // d.innerText='\ud83d\udd6f';
          d.innerText='\u{1f56f}';
          x=Math.random()*w;
          y=Math.random()*h;
          d.style.position='absolute';
          d.style.left=`${x}px`;
          d.style.top=`${y}px`;
          document.body.append(d);
        }
      }
    </script>
  </head>
  <body onload="light()">
  </body>
</html>
