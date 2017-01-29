Ruby on Rails Tutorial sample application



This is an implementation of the Product Commenting application for extra credit on the Shapeways coding test application. 

[* Language: Ruby on Rails

by [Thomas List](http://github.com/tlist/)



## Getting started



To get started with the app, clone the repo and then install the needed gems:



```

$ bundle install --without production

```



Next, migrate the database:



```

$ rails db:migrate

```



Finally, run the test suite to verify that everything is working correctly:



```

$ rails test

```



If the test suite passes, you'll be ready to run the app in a local server:



```

$ rails server

