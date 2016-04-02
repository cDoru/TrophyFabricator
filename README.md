# TrophyFabricator
Three js base 3d viewer
 
Main function:
-Stl Model can be uploaded or and viewed using the this function;
<script>
      window.onload = function(){
        mad = new Madeleine({
          target: 'target',
          data: 'models/skull.stl',
          path: './src'
        });
 <script>
  include this with the model path to be displayed.
  You can also use a input button to  upload a file using this function;
 <script> 
  Lily.ready({
          target: 'upload',
          file: 'stlFile',
          path: './src'
        });
      }; 
  </script>
  -The color can be used to change the model render color.
  
  
