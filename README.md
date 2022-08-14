 1)
    var obj = [
          { person: "Name 1", age: "2", company: "GUVI" },
          { person: "Name 2", age: "5", company: "GUVI geek" },
          { person: "Name 3", age: "8", company: "GUVI geek network" },
        ]
    use the above JSON to iterate over all for loops (for, for in, for of, forEach)
  
   JSON ARRAY:
   ............. 
      var obj = [
          { person: "Name 1", age: "2", company: "GUVI" },
          { person: "Name 2", age: "5", company: "GUVI geek" },
          { person: "Name 3", age: "8", company: "GUVI geek network" },
        ]
        
        FOR LOOP
     ..............
     for(var i=0;i<obj.length;i++)
         {

             console.log("details of person ",i, ":" , obj[i] )
         }

    OUTPUT:
      --------
               details of person  0 : {person: 'Name 1', age: '2', company: 'GUVI'}
index.js:104   details of person  1 : {person: 'Name 2', age: '5', company: 'GUVI geek'}
index.js:104   details of person  2 : {person: 'Name 3', age: '8', company: 'GUVI geek network'}
  

  FOR IN LOOP:
   ----------------
  for(var details in obj)
     {
        console.log("details of person ",details, ":" , obj[details] )

     }

   OUTPUT:
  ----
details of person  0 : {person: 'Name 1', age: '2', company: 'GUVI'}
index.js:89 details of person  1 : {person: 'Name 2', age: '5', company: 'GUVI geek'}
index.js:89 details of person  2 : {person: 'Name 3', age: '8', company: 'GUVI geek network'}
    
   FOR OF LOOP:
   .............
    for(var person of obj)
       {
            console.log("details of a person are :",person)
       }
   OUTPUT:
  .............  
details of a person are : {person: 'Name 1', age: '2', company: 'GUVI'}
index.js:95 details of a person are : {person: 'Name 2', age: '5', company: 'GUVI geek'}
index.js:95 details of a person are : {person: 'Name 3', age: '8', company: 'GUVI geek network'}

  FOR EACH LOOP:
 ................
 obj.forEach((person, details)=>console.log("details of person ",details, ":" , person ))

    OUTPUT:
  ...........
details of person  0 : {person: 'Name 1', age: '2', company: 'GUVI'}
index.js:98 details of person  1 : {person: 'Name 2', age: '5', company: 'GUVI geek'}
index.js:98 details of person  2 : {person: 'Name 3', age: '8', company: 'GUVI geek network'}

..................................................

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

 for(let details in sreekanth_Resume)
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
