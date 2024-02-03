// # Date 함수
// let date = new Date();     
// 오늘의 날짜 Thu Feb 03 2024 15:30:00 GMT+0000
// # Date 함수로 오늘의 년, 월, 일 데이터 구하기  
//  let year = date.getFullYear();                          //2024
//  let month = ("0" + (1 + date.getMonth())).slice(-2);    //02
//  let day = ("0" + date.getDate()).slice(-2);             //03
//---------------------------------------------------------------------------------


// 오늘의 날짜를 년(yyyy)월(MM)일(dd)을 따로 사용할 수 있도록 JSON 형식으로 반환하는 함수
function getToday() {
    let date = new Date();                           // 오늘의 날짜 Thu Feb 03 2024 15:30:00 GMT+0000
    
    return {
        year: date.getFullYear(),                          //2024
        month: ("0" + (1 + date.getMonth())).slice(-2),    //02
        day: ("0" + date.getDate()).slice(-2),             //03
      };
  }
export defalt getToday();


//---------------------------------------------------------------------------------
import getToday from "../components/GetToday";

const todayInfo = getToday;
const { year, month, day } = todayInfo;
const todayValue = year + month + day;

// 출력
console.log("JSON:",todayInfo);        //JSON: {year: 2024, month: '02', day: '03'}
console.log("년:", year);              //년: 2024
console.log("월:", month);             //월: 02
console.log("일:", day);               //일: 03
console.log("년월일:", todayValue);    //년월일: 20240203
