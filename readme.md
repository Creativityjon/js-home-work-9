JS - 10
Theme: DOM MONUPULATION

- Atribute / class, id, name, alt, type, value, placeholder, data, set

let loginForm = document.querySelector('#login_form');
console.log(loginForm.id); -> return the loginForm id

passwordForm.type = "color";
// typini ozgartirish  

userNameForm.placeholder = "enter phone number";
// js da turip placeholderi textini ozgartirish

let value = passwordForm.getAttribute("placeholder"); // get
console.log(value);
// output: enter phone number
// harqande html elementga getAttribute yozib agar atributi nomini yose uni value sini qaytarib oberadi

passwordForm.setAttribute("placeholder", "enter secret key"); // set
// output: enter secret key
// bunda teskarisi ishlidi, setAttribute orqali biron bir tanlangan elementga setAttrubute dimiz uning atribute nomini yozamiz ikkinchi yozilgan  value placeholderga yangi qiymat bolib tushadi

