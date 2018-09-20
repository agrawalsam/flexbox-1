# Flexbox-1
Although flexboxs are indeed powerfull, they most powerfull thing I felt was while using order.
Let's begin the journey: 
  # Definition 
    The order property specifies the order of a flexible item relative to the rest of the flexible items inside the same container.
    Note: If the element is not a flexible item, the order property has no effect.
  # Tree Structure
  Parent element on which display=flex;
  |----Child element
  |----Child element 
  |----Child element
  |----Child element
  # Usage
  In HTML file:
  <div class="flex-container">
        <div class="one">
          <!-- Components Inside-->
        </div>
        <div class="two">
          <!-- Components Inside-->
        </div>
        <div class="three">
          <!-- Components Inside-->
        </div>
        <div class="four">
          <!-- Components Inside-->
        </div>
  </div>
  
 In CSS file :
 .file-container{
    display:flex;
    justify-content: center;
 }
 .one{
   order:0;
 }
 .two{
   order:0;
 }
 .three{
   order:0;
 }
 .four{
   order:0;
 }
 
 # Controls:
 The order attribute works in ascending order. The element whose order is less is displayed in the left side of observer.
 The element whose order is more is displayed in the right side of observer. 
 The element along with all its styling and content is interchanged values without righting any other verbose css.

