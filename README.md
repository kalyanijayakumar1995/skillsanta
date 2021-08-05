# skillsanta

Question 1 :


Answer : var dateToday = new Date('October 15, 1996 05:35:32:77 GMT+11:00')
             var a = dateToday.getUTCMilliseconds();
             documement.write(a);
             
Question 2 : function displayLibraryInformation( )
              {
                }
             var library =  [
                    {
                         author : ' Bill Gates',
                         title : ' The Road Ahead',\
                         readingStatus: true 
                    },
                    {
                         author : 'Steve Jobs',
                         title : 'Walter Issacson',
                         readingStatus : true
                    },
                    {
                         author : 'Suzanne Collins',
                         title :'Mockingjay : The Final Book of the Hunger Games',
                         readingStatus : false 
                    }];

           displayLibraryInformation( );
Question 3 : 
       The code will give output as Rohit . Here Emp1 object got company as prototype property . Delete Operator doesnt delete prototype property . Emp1 object doesnt have
       company as its own property .

Question 4 : These two functions will not return same output.
         foo2 returns undefined without any error being thrown. The reason for this has to do with the fact that semicolons are technically optional in JavaScript 
        (although omitting them is generally really bad form). As a result, when the line containing the return statement (with nothing else on the line) is encountered in         foo2(), a semicolon is automatically inserted immediately after the return statement.No error is thrown since the remainder of the code is perfectly valid, even though it doesn’t ever get invoked or do anything (it is simply an unused code block that defines a property bar which is equal to the string "hello").
       This behavior also argues for following the convention of placing an opening curly brace at the end of a line in JavaScript, rather than on the beginning of a new line. 

Question 5. output : [1, 28, 39, 17, 32.5]

Question 6. const set = new Set(['Beethoven','Mozart','Chopin','Chopin']);
       set.delete('Beethoven');
       console.log(set);
       
 Question 7:     const operatingSystem = {
    name: 'Ubuntu',
    version: 18.4,
    license: 'Open Source'
};

// Get the object key/value pairs
const entries = Object.entries(operatingSystem);

console.log(entries);  

Question 8. const name = {
                              firstName: "Philip",
                              lastName: "Fry"
                            };

                                                   // Initialize another object
      const details = {
                               job: "Delivery Boy",
                              employer: "Planet Express"
                             };

                                                  // Merge the objects
      const character = Object.assign(name, details);

      console.log(character);

        
Question 9. gimli.greet();

Question 10 : function Hero (name,level)
{
name = name ;
level = level ;
}

class Hero {
    constructor(name, level) {
        this.name = name;
        this.level = level;
    }

    // Adding a method to the constructor
    greet() {
        return `${this.name} says hello.`;
    }
}
