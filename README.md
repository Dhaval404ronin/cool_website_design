# cool_website_design
a website created with simplest html css and gsap javascript easy


used G-sap 
first linked scroller and changed appearrence as we scroll. that's main thing that i learned. also discoverd how i follow my cursor and change that appearnce as i follow.

second is infinite scroll :
#scroller1{
    display: inline-block;
    white-space: nowrap;
    animation-name: scroll;
    animation-duration: 40s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
}
@keyframes scroll {
    from {
      transform: translateX(0);
    }
    to {
      transform: translateX(-100%);
    }
  }

have 1-2 bug in animation but does not go away when i simply write same thing again it works fine for some time like container animation of small to big.
