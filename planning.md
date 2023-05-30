CSS Styling:
Form background color:linear-gradient(90deg, rgba(0,0,0,1) 0%, rgba(12,115,92,1) 0%, rgba(19,186,149,0.9904294481464461) 87%); 
Send icon: <img width="64" height="64" src="https://img.icons8.com/glyph-neue/64/FFFFFF/sent.png" alt="sent"/>

On empty span, apply: 

{ 
  position:absolute; 
  width:100%;
  height:100%;
  top:0;
  left: 0;

  z-index: 1;

  /* fixes overlap error in IE7/8, 
     make sure you have an empty gif */
  background-image: url('empty.gif');
}  