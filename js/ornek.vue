new Vue({
    el: "#app",
    data: {
        result:""        
    },
    methods: {
        add: function(){
            number1=+document.getElementById("number1").value,
            number2=+document.getElementById("number2").value,
            this.result=number1+number2
        },

        sub: function(){

            number1=+document.getElementById("number1").value,
            number2=+document.getElementById("number2").value,
            this.result=number1-number2

        },

        div: function(){
            number1=+document.getElementById("number1").value,
            number2=+document.getElementById("number2").value,
            this.result = parseFloat(number1/number2)
        }, 

        mul: function(){
            number1=+document.getElementById("number1").value,
            number2=+document.getElementById("number2").value,
            this.result = number1*number2
        }
    }
})