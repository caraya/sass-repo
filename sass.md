#SASS and the SASS Library

This projects aims to build a repository and a body of knowledge for using SASS to generate the CSS used in eBooks. 

I chose SASS as my pre-processor option because I consider it the cleanest solution of them all. It leverages a user's knowledge of CSS and allows some awesome things that are impossible to do with standard CSS elements. 

##What is SASS

SASS (Syntactically Awesome Style Sheets) is a superset of CSS3 which offers additional functionalizty such as: variables, nesting, mixins, selector inheritance, include files and live updates. We will cover these elements briefly.

###Variables

Rather than having to type the same name or value over and over again, SASS allows you to create variables that you can use throughout your stylesheets. For example we can define our colors as variables and then use the variables wherever we would use the color definition. 

```sass
$red: #cc092f;

/* Link Formatting */

a {
  color: $red;
}
```

The main advantage of variables is that we need to only change one value and then recompile the stylesheet for the changes to be reflected everywhere the variable appeared in the document. 

###Nesting

How many times you've found yourself creating CSS like this.

```sass
h2 {
  font-size: 36pt;
}

h2 .warning {
  color: #f00;
}

h2 .important {
  font-weight: bold;
}
```

With SASS you declare the classes as nested attributes without having to retype the base attribute. Using SASS the above snippet would be coded as follows:

```sass
h2 {
  font-size: 36pt;

  .warning {
    color: #f00;
  }

  .important {
    font-weight: bold;
  }
}
```
And it will produce the same result as it would coding straight CSS. In the example above it's easy to see the result

###Install SASS

###Build index file

##Compile Stylesheets

##How do the snippets work

###What they are

###Creating your own

##License

[MIT](http://caraya.mit-license.org/) 
