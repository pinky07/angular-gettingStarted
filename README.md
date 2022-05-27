1.for call any service need to inject withine constructor 2. for adding any route/path need to add in app.module.ts, activeRoute is for local path variable
jo humre local/specific url ka info rkhta hai
3.jab compoonent create krte hai tab 3 files create hoti hai ts/html/css 4. jab service create krte hai tab sirf service generate hota hai 5. ts file is like main/service/method/function with body hume method call html me krna hota hai, mostly event bvinding me jaise button/click me 6. @input ka use internal value pass krne ke liye krte hai ex; parent compoonent se child me
7.@output/eventEmitter/emit() ka use value/data pass krne ke liye to parent component
input/output ka use chil/parent communicate krne ke liye hota hai jo ki angularcore me hota hai 8. koi api(Get/post/put/delete) ko use krne ke liye hume HTTPclient ka use krna hota hai
service ke ander 9. service file and ts file dono ka kaam alaga2 hota hai 10. kisi bhi external jar/lib ko use krne ke liye import krne ke bad usko inject bhi krna hota hai, jnha pe use kr rahe hai 11. app.module --> pom.xml ke jaise kaam krta hai jnha sare lib/dependcy ko registre krn hota hai 12. command to generate component ng generate component XXXXXXX 13. jab bhu hum new component create krte hai uske path ko app.module.ts me add krte hai ki particular view knha/kis url me dikhe 14. service ko constructor ke ander inject krte hai kisi bhi component me use krne ke liye, jab bhi koi service->component communicate krna hai hoga tab2
constructor me inject krne ke bad us variable ko local variable ke refeence ke sath use krnge 15. mostly ts file ke ander service call/inject/method define ye sab hota hai
16.app.component.html ek tarike se java ke jais emain class hai,jnha se start me kisi ek service/method/html/ts/componet ko call krna hota haia
17. java me model class ke jaisa ynha interface hota hai lekin ye koi packgae specific nhi hota hai..mostly root level me hota hai.
 without setter/getter
 ab jab setter/getter hai hi nhi to directly value assign krnege jnha bhi use krenge
 18. <span> kab use krte hai, jab array/list/key/ ko one by one print krwana ho tab, aur <div> value ko printg krwane ke liye hota hai{{}} wala
  ek condition ke liye 1 div lga dete hai
   <input> tag ke sath me <lable> bhi lgate hai jo ui me simple msg display krte hai aur dono ka id same hota hai
 19.Pipes are a good way to format strings, currency amounts, dates and other display data. 
 20.html/form ka main purpose hota hai user se input lena aur usko display krwana, to form ke input tag ke ander ek aisa element lenge 
  jo userinput ko store kr ske aur bad me khin bhi display krwa sake
  angular me iske liye ngModel use krte hai, naam sunne me model lag rha hai lekin bas ye ek global variable ke jaise value store krta hai
  with syntax [(ngModel)]="ValueWeWantToStore"
  21. isme boolean ko variable?:array aise assign krte hai, aur fir bad me sidhe ngif use keta hai variable ke sath
  22. client/angular me jo bhi java/BE se communication hoga wo sab asyns hoga/ bcz db se be fetch krne me time lgta hai  lekin Observable iska just opposit kaam krta hai, means no wait, ye sirf mock server ke liye sahi rhta hai
 
https://malcoded.com/angular-cheat-sheet/
