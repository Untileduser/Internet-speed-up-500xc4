function TurnUpSpeed(_max400_, loop) {
    
document.getElementById("speed-value").innerHTML = _max400_
    if (loop==true) {
            
        document.getElementById("speed-value").innerHTML = _max400_
        TurnUpSpeed(_max400_, loop)
    }
}
//paste in url: xjavascript: TurnUpSpeed(380, false) and remove the "x"
