#Week 4 Session 8

Today in class Ali the tutor took us through express.js to start it is downloaded through npm.
The following are the examples we used in class, I am yet to revise to gain an understanding of
today's class.

The Scenario is a customer requesting a booking for a table and the response and what is next.

**Require:**   (Customer requires a table for many at a restaurant)

var express = require(‘express’)       // this is a framework 
var app express( )

**Middleware:** (is an action) (the manager/express need to find a table) 

	app.use (‘/table’, (req, res, next) =>
			{

});

app.use(function( req, res, next ))	//app.use((req, res, next) =>
{
	var booking = req.booking;	//request a booking
	var age = req.age;		//request the age because there is alcohol
	
	if (booking && age)		//if the booking and age met requirements then NEXT( )
{
		next( )
}
} 

**Routes:**

Executing routes – booking a table for many with all people of age 
 app.get  (‘/table/:amount’, (req, res, next) =>

{
var dinner =req.params.amounts
res.send(‘looking for table’ + ‘dinner’)
 })
req = {
params:{
amounts:4
}
}

Const express = require(‘express‘);

Const tableRoute = express.router()
tableRoute.use ((req, res, next) =>{
var booking = req.booking; 
var age = req.age;
{
Next ()
}
});
TableRoute.use (‘/bar’,function(req, res, next){
var age = req.age 
if ( age> =18> < next( ) >)
}

**app.listen:** code will not run unless you run this code

App.listen(3000) {
    console.log(‘running port 3000’)
}
 
**Today was a soft introduction to express.js but my focus this weekend will be:**

    * getting my wireframes done
    * storyboards completed
    * report finished
    * tutorial for react 1 
    * tutorial on react website