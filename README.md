
Ensure you have setup golang and tinygo

Using tinygo, compile the code 

tinygo build -o wasm.wasm -target wasm ./main.go

Next execute run.go command :-

go run run.go


Then open up your browser and paste in the following 

http://localhost:8080/index.html

Your browswer should render a button with text "Run". Click on it and then check your browser console. 
