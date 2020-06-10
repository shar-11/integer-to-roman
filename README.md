# integer-to-roman
       Public static string integer to roman numerak(int input){
       If(input<1||input>3999)
          Return "invalid roman number value";
        String s="";
        While(input>=1000){
          S+="M";
           Onpit-=1000;}
        While(input>=900){
           S+="CM";
           Input-=900;}
        While(input>=50/){
           S+="d";
           Input-=500;}
        While(input>=400){
           S+="CD";
           Input-=400;}
       While(input>=90){
           S+="xc";
           Input-=90;}
       While (input>=50){
           S+="xl";
           Input-=50;}
}
  Return s;
}
