new Vue({

  el:'#content',

  data:{
   show:false,
   port:'',
   res:'',
   abo:'',
   see:'',
   seen:'',
   saw:true,
   shows:true,
   shown:'',
   color:'#1556c9',
   colors:'',
   aboutc:'#1556c9',
   portc:'',
   resc:''
   

  },

  methods:{


   pera(){
    this.show = true
    this.port = 'Portfolio'
    this.res = 'Resume' 
    this.abo = 'About'   
    
   },
    
   

   
   nopera(){
    this.show = false
    this.port=''
    this.res=''
    this.abo =''
   },

   resume(){
    this.see = true
    this.seen = false
    this.saw = false
    this.resc = '#1556c9'
    this.portc = ''
    this.aboutc = ''
    
   },

   portfolio(){
    this.seen = true
    this.see = false
    this.saw = false
    this.portc = '#1556c9'
    this.resc = ''
    
    this.aboutc = ''
   },

   about(){
    this.saw = true
    this.seen = false
    this.see = false
    this.aboutc = '#1556c9'
    this.resc = ''
    this.portc = ''
    
   },

   front(){
     this.shows=true
     this.shown = false
     this.color='#1556c9'
     this.colors =''
   },

   back(){
    this.shows=false
    this.shown = true
    this.color = ''
    this.colors = '#1556c9'
   }
  }


});

