# Swift Tip Calculator
Because sometimes a TODO list is too hard as a first app, here's a tip calculator!

## What is this

![animated gif demo of calculating a tip for $42.50](preview.gif)

This is an implementation of the Swift tip calculator built by following this wonderful [tutorial video](http://vimeo.com/102084767) published by CodePath.

Time spent: 3 hours

Completed stories:

 * [x] Required: Calculates an [accurate](https://www.youtube.com/watch?v=HrzhqXGcm68) tip based on user input
 * [x] Required: A settings button displays information about the app
 * [x] Optional: User can set a default tip value from settings

## What's different

- There is one place where this app's implementation of [`ViewController.swift`] diverges from the code featured in the video. At [21:45](http://vimeo.com/102084767#t=21m45s) an internal method, `bridgeToObjectiveC` is used. I use `as NSString` instead.
        var billAmount = (billField.text as NSString).doubleValue

- A settings modal has been added. It allows the user to set a default tip.

## Credit
- GIF created with [LiceCap](http://www.cockos.com/licecap/).
- [@timothy1ee](https://github.com/timothy1ee) for the great [tutorial video](http://vimeo.com/102084767) 

## License

MIT


