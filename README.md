let username : string = "Rafiq Ullah Khan"
let pw : string = "karachi1234"
let PIN : string = "1234"

if(username == "Rafiq Ullah Khan" && pw == "karachi123"){
    console.log("Please Proide PIN") 
    if(PIN == "1234"){
        console.log ("Welcome Rafiq Ullah Khan")
    }
    else {
     console.log("incorrect user")
 } 
} 
else if (username == "Rafique Ullah Khan" && pw == "karachi123"){
    console.log("Please Proide PIN") 
    if(PIN == "1234"){
        console.log ("Welcome Rafique Ullah Khan")
    }
    else {
     console.log("incorrect user")
 } 
}
else {
    console.log("Incorrect Username or password")
 }
