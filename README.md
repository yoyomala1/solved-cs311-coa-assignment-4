Download Link: https://assignmentchef.com/product/solved-cs311-coa-assignment-4
<br>
<span class="kksr-muted">Rate this product</span>

Upgrade the simulator to a pipelined core model.

• Update your simulate function to a loop that looks something like this: while(not end of simulation)

{

}

performRW performMA performEX performOF performIF increment

clock by 1

Each stage must operate on the output generated by the previous stage in the previous cycle. If the input latch to the stage has invalid content (e.g., in the very first cycle, MA-RW latch has invalid content), the stage must do nothing.

• Implement data interlocks and control interlocks. To Be Submitted

<ul>

 <li>A zip of the source files. They have to pass the test cases given for the previous assignment.</li>

 <li>A report that contains a table with

  <ul>

   <li>–  the number of cycles taken by each benchmark program,</li>

   <li>–  the number of times the OF stage needed to stall because of a data hazard,</li>

   <li>–  the number of times an instruction on a wrong branch path entered the pipeline.Comment on your observations. Correlate with the nature of the bench- marks.1</li>

  </ul></li>