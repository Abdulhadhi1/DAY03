 1)
    var obj = [
          { person: "Name 5", age: "6", company: "GUVI" },
          { person: "Name 2", age: "5", company: "GUVI geek" },
          { person: "Name 3", age: "8", company: "GUVI geek network" },
        ]
    use the above JSON to iterate over all for loops (for, for in, for of, forEach)
  
   JSON ARRAY:
   ............. 
      var obj = [
          { person: "Name 5", age: "6", company: "GUVI" },
          { person: "Name 2", age: "5", company: "GUVI geek" },
          { person: "Name 3", age: "8", company: "GUVI geek network" },
        ]
        
        FOR LOOP
     ..............
     for(var i=0;i<obj.length;i++)
         {

             console.log("details of person ",i, ":" , obj[i] )
         }

..............................................
  

  FOR IN LOOP:
   ----------------
  for(var details in obj)
     {
        console.log("details of person ",details, ":" , obj[details] )

     }

..........................................................
    
   FOR OF LOOP:
   .............
    for(var person of obj)
       {
            console.log("details of a person are :",person)
       }
.........................................................................

  FOR EACH LOOP:
 ................
 obj.forEach((person, details)=>console.log("details of person ",details, ":" , person ))
 
 
.....................................................................................................................



 2. Create your own resume data in JSON format
 .................................

 let Abdul Hadhi_Resume={

    Name:"A Abdul Hadhi",
    DOB:"04-12-1999",
    UnderGraduation:"BCA",
    Branch:"computer application",
    YearOfPassout:2020,
    UGpercentage:87.9,
    Languages_known :"tamil,english"  
  }

 for(let details in Abdul Hadhi_Resume)
      {
             console.log(`${details}:$Abdul Hadhi_Resume[details]}`)
       }

 OUTPUT:
.............
             Name:A Abdul Hadhi
index.js:121 DOB:04-12-1999
index.js:121 UnderGraduation:BCA
index.js:121 Branch:computer application
index.js:121 YearOfPassout:2020
index.js:121 UGpercentage:87.9,
             Languages_known:"tamil,english"
