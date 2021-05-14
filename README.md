# VueInfo

$workshop2

(Create) <br>
1. 스토리지에서 저장된 데이터 가져오기 <br>
2. 가져온 데이터를 생성한 객체에 파싱해주기 <br>
3. 입력된 데이터를 추가하고, 스토리지에 저장 <br>
4. 
Localstorage : 스토리지에 저장된 값을 가져온다. <br>
JSON.parse() : 스토리지에서 가져온 값을 newBoard에 JSON으로 파싱 <=> JSON에서 스토리지로 Set할땐 JSON.stringify()로 변환해준다. <br>
books에는 필요한 값을 넣어준다. 

(List) <br>
return x.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ","); 3자리마다 , 찍기 <br>

(view) <br>
const params = new URL(document.location).searchParams; // url에서 파라미터 정보 가져오기 <br>
return str.replace(/(?:\r\n|\r|\n)/g, "<br />"); // 문자열에서 enter를 치면 그대로 적용 <br>

(modify) <br>
created에서 params으로 받은 값을 스토리지에 있는 값(isbn)과 비교하여 this.??에 넣어줌 (빈칸일 때 알림, 수정 용도) <br>

(delete) <br>
params에서 받아온 값을 기존에 스토리지에 저장되어 있는 값과 비교하여 다른 것들만 filter하여 booklist에 넣어준다. <br>




