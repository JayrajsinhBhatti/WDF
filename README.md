# WDF

//INTERVIEW 

//js slider code
function showslide() {
    document.getElementById("slider").style.transform = `translateX(-${index * 400}px)`;
}
function nextslide() {
    index = (index + 1) % slides.length;
    showslide();
}
function prevslide() {
    index = (index - 1) % slides.length;
    showslide();
}
