# javascript_30  day_01

step 1. bulid keybaord,and find audio,and then make sure html & css ready.

step 2. bulid a little html like demo, for output key & keyCode on screen.

problem: can't call element by className 
        "document.getElementByClassName("keyCode").innerHTML = e.keyCode.toString();"
   because ClassName return array,must call by 
        "document.getElementByClassName("keyCode")[0].innerHTML = e.keyCode.toString();"
   ,even if you only have one element with this class.

step 3. bulid js with demo, finish this project!

problem: keys array can't get value, because put script link in the head, js runs before html
         "const keys = document.querySelectorAll(".key");"
   ,after half hour finding typing error in js, finally figure out calling js in wrong place,
   this is a good experience!!!
