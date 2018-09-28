_it function removed extra charactes_
**use it at**

`import clear from "clear-code";`

`clear(string, length, entityMap, replases)`

you string

    `string ( string )`

set max length

    `length ( number ) default = 0`

set entityMap default = {'&': '','<': '','>': '','"': '',"'": '','\`': '','=': ''}

    `entityMap ( object ) - you string`
    
set replases default = /[&<>"'\`]/g

    `replases ( regular ) - you string`
    
**exapmles defaul settings**

    `let result = clear('12`3'45678=', 5)`
         console.log(result) - return 12345

**OR use some setting**

    let result = clear('12345678', 5, {'4':'g','1':'t'}, /[4,1]/g)`
    console.log(result) - return `t23g5`
    

    
