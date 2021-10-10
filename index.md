var names=["Elhoucine", "Jhom", "Jen", "Paul", "Frank" , "Larry" , "Paula ", "Laura", "Jim"];

for (i=0; i < names.length; i++){
  var eersteletter=names[i].charAt(0).toLowerCase();
  var counter=i+1;
  
  if(eersteletter=='j'){
    console.log(counter + "- "+ "Good Bye" + " "+ names[i]);
  }else{
    console.log(counter + "- "+ "Hello" + " "+names[i]);

  }};
