- An element's margin controls the amount of space between an element's border and surrounding elements.

- Here, we can see that the blue box and the red box are nested within the yellow box. Note that the red box has a bigger margin than the blue box.

- When you increase the blue box's margin, it will increase the distance between its border and surrounding elements.

Reference-image: 
![margin image][margin]

[margin]: margin.png "Margin"


- If you set an element's margin to a negative value, the element will grow larger.

`
.red-box {
    background-color: crimson;
    color: #fff;
    padding: 20px;
    margin: -15px;
  }
`

`
.blue-box {
    background-color: blue;
    color: #fff;
    padding: 20px;
    margin: 30px;
  }
`

Reference-image: 
![negative-margin image][negative-margin]

[negative-margin]: negative-margin.png "Margin"

