Don't forget to do <code>()=>(foo(arg))</code> when passing in arguments to a function in a handler, e.x. onClick. <br />

Map things out when you have objects in a list that you want to pass into a component. <br />

Draw a tree diagram out for big projects. <br />

Add lots of components. <br />

Use services files to not clunk up your App.js. <br />

If you're project is feeling mucky, just restart. <br />

Template for changing a state:
<code>
  const [a, b] = React.useState(['hi','world']);
  const dup = [...a]; //won't work without spread operator
  b(dup);
</code><br />

Playing devils advocate, but use Math.random() when you don't have reliable keys. <br />
