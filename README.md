# VueInfo

$workshop2

(Create) <br>
1. 스토리지에서 저장된 데이터 가져오기 <br>
2. 가져온 데이터를 생성한 객체에 파싱해주기 <br>
3. 입력된 데이터를 추가하고, 스토리지에 저장 <br>

Localstorage : 스토리지에 저장된 값을 가져온다. <br>
JSON.parse() : 스토리지에서 가져온 값을 JSON으로 파싱 <=> JSON에서 스토리지로 Set할땐 JSON.stringify()로 변환해준다. <br>

(List) <br>
return x.toString().replace(/\B(?=(\d{3})+(?!\d))/g, ","); 3자리마다 , 찍기 <br>

(view) <br>
const params = new URL(document.location).searchParams; // url에서 파라미터 정보 가져오기
return str.replace(/(?:\r\n|\r|\n)/g, "<br />"); // 문자열에서 enter를 치면 그대로 적용




