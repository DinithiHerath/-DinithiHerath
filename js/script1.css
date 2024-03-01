document.addEventListener("DOMContentLoaded", function(event) {
    // Update section height when the page loads or the window is resized
    updateSectionHeight();
  
    // Update section height when the content changes
    window.addEventListener("resize", updateSectionHeight);
  });
  
  function updateSectionHeight() {
    var sections = document.getElementsByTagName("section");
    for (var i = 0; i < sections.length; i++) {
      sections[i].style.height = "auto"; // Reset the height
      sections[i].style.height = sections[i].offsetHeight + "px"; // Set the new height
    }
  }
  