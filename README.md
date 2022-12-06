<!-----------------------------------Converter----------------------------------------->

# Digit Converter :-

It is a Digit Converter this Converter convert Binary to dacimal, dacimal to hexadecimal,
and 10 further conversion performed by it.. It have Two select Box 1st is "From" section and 
2nd is "To" section... and it also have Two input box 1st for input value and 2nd for Output.
It have three buttons 1st for Conversion performance, 2nd for swap the select box and input 
box swaping performance, and 3rd one is using for the reset the converter.... 


# What was my thinking while making this project...

In this radix converter i use HTML CSS and JavaScript for functionality. In this project 
i tried redix converter formula first than after that i search on google to make this converter 
in a efficient way.... after that i refer the ("https://developer.mozilla.org/en-US/docs/Web/
JavaScript/Reference/Global_Objects/Number/toString") ("https://developer.mozilla.org/en-US/
ocs/Web/JavaScript/Reference/Global_Objects/Number") some websites and i follow the idea how 
to convert binery to hexadacimal and all..... 


# First i made Design of the Project....

While making this project i use HTML and CSS. I tried to give it a decent look.... 
In the project i use input box, select box, div's, buttons and etc...
For the styling i use a dark color for night mode and light color for day mode...
i appied hover on the button. I use border to make it attractive..... 


# For the functionality

In JS part i get all the HTML element in JS varible and use this variable's for next steps...
For the button functionality i use addEventListener in this event i make 12 conditions for the 
12 conversion... I mantioning here first conersion operation...........

Eg:-

 if(val1 == 2 && val2 == 10){
        var text = enterValue.value;
        if(!isNaN(Number('0B' + text))){
            var convertedVal = (parseInt(text, 2));
            outputValue.value = convertedVal;
            console.log(convertedVal);
            console.log(outputValue.value);
        }else{
            outputValue.value = "Please Enter Valid Number";
        }
    }

it is a simple Binary to Decimal conversion proccess and i use as it is proccess for the further conversion.....

# my learning in this project

I choose this project beacause i know that It is a challanging project and when i will complete it i will learn a lot of things... 
first of all i don't know how to convert digits but for the project i learn about it and first i tried with that after that io go to some efficient way.... now i feel that there is a lot of way to do a particular project... 
i learn how to swap two select box and input area..... i tried a lot of thing for do this task and finally i found a efficient way i use simple swaping method.. 
In this project i use some DOM menthod and learn more about that how to use addEventListener how to get element in JS variable and all.... in this project i 
applied various condition so this part helped me in my logical learning......
overall i am grateful to choose this project..... 
