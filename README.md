# Test Responsiveness
Test Responsiveness is a javascript based easy to use tool, that lets you show your clients the web page responsiveness.

##### Why Test Responsiveness?
  - Free
  - Easy to use (include and use)
  - Bingo...!!! You're done.


## Installation and Usage

### Installaiton
Include the test_responsive.js in head tag of your webpage.
```sh
<head>
<!-- Your can insert anywhere in head -->
<script src="https://mutafaf.github.io/TestResponsiveness/test_responsiveness.js"></script>
</head>
```

### Add basic HTML
Create two divs with unique IDs e.g. `btn-group-container` and `frame-container`.
```sh
<body>
    <div id='btn-group-container'>

    </div>
    <div id='frame-container'>

    </div>
</body>
```

### Call the `createPlayground()`
Insert the following script right before end of your `body` tag.

```sh
<body>
    <!-- your body code -->

    <script type="text/javascript">
        document.addEventListener("DOMContentLoaded", function(event) {
          //insert URL here
          var url = "mutafaf.com";

          //insert parent container ID for buttons group
          var btnGroupParent = "btn-group-container";

          //insert parent container ID for frame
          var frameParent = "frame-container";

          createPlayground(url,btnGroupParent, frameParent);
        });
    </script>

</body>
```


### Explaination

Call the createPlayground() function with 3 parameters.
The first one is `URL` to load.
Second is `btn-group-container`,  ID of parent `div` for button group.
Third is `frame-container`,  ID of parent `div` where you want the website to load.


## Author
[Mutafaf Wahhaj] is a Full Stack Web Developer and have expertise in various modern technologies.
[Linkedin](https://www.linkedin.com/in/mutafaf/) | [Twitter](http://twitter.com/mutaffaf) | [StackOverFlow](https://stackoverflow.com/users/7360347/mutafaf)

License
----

MIT


**Free Software, Hell Yeah!**

   [Mutafaf Wahhaj]: <http://mutafaf.com>
