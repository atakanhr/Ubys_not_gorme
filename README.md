# Ubys_not_gorme
Her not için de anket mi olur ...


Tarayıcınızın konsoluna bu kodu yapıştırın.


const array1 = _StudentCourses
array1.forEach(myFunction)
console.log("ATAK4NHR")
function myFunction(item, index, arr) {
  
  if(typeof arr[index]["ExamPoints"][0] !== 'undefined'){
    console.log(arr[index]["CourseCode"]+" "+arr[index]["CourseName"])
    console.log(arr[index]["ExamPoints"][0]["ActivityName"]+"|"+arr[index]["ExamPoints"][0]["ExamPoint"])
  }
  else{
  console.log(arr[index]["CourseName"]+" ||NOT BULUNAMADI||")
  }
   if(typeof arr[index]["ExamPoints"][1] !== 'undefined'){
    console.log("FİNAL"+"|"+arr[index]["ExamPoints"][1]["ExamPoint"])
  }
   if(typeof arr[index]["ExamPoints"][2] !== 'undefined'){
    console.log("BÜT"+"|"+arr[index]["ExamPoints"][2]["ExamPoint"])
  }
  
}
