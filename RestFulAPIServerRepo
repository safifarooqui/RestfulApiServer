var express = require('express');
var app = express();
var fs = require("fs");
app.get('/listUsers', function (reg, res) {
fs.readFile( dirname + "/" + "users.json", 'utf8', function (err, data) {
console.log( data );
res.end( data );
});
} )
var server = app.listen(8081, function() {
var host = server.address().address
var port = server.address().port
console.log("Example app listening at http://8s:8s", host, port)
} )
