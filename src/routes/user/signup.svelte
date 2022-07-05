<div
  class=" sticky top-0 text-xl font-bold px-4 h-12 flex items-center border-b bg-white"
>
  회원가입
</div>

<div class="flex p-4">
  <span class="pr-3">
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="22"
      height="22"
      viewBox="0 0 24 24"
      fill="none"
      stroke="red"
      stroke-width="2"
      stroke-linecap="round"
      stroke-linejoin="round"
      class="feather feather-alert-circle"
      ><circle cx="12" cy="12" r="10" /><line
        x1="12"
        y1="8"
        x2="12"
        y2="12"
      /><line x1="12" y1="16" x2="12.01" y2="16" /></svg
    >
  </span>
  <span class="text-sm text-gray-400 font-bold"
    >포지션 지원 시 인사 담당자와의 연락을 위해<br />개인정보를 정확하게 입력해
    주세요.</span
  >
</div>

<label for="" class="px-4 pt-7 text-sm font-bold block text-gray-500 mb-2"
  >이름</label
>
<div class="px-4">
  <input
    type="text"
    class="w-full  h-14 border-gray-300 rounded-md  placeholder-neutral-400 peer"
    placeholder=" 이름을 입력해 주세요."
  />
</div>

<label for="" class="px-4 mt-4 text-sm font-bold block text-gray-500 mb-2"
  >휴대폰 번호</label
>

<div class="flex justify-center px-4">
  <select
    class="h-14 rounded-md w-full border border-gray-300 text-black font-bold"
  >
    <option selected>Republic of Korea (대한민국) +82</option>
  </select>
</div>

<div class="flex gap-2 px-4 mt-2">
  <input
    type="text"
    class="flex-1 h-14 border-gray-300 font-bold rounded-md text-sm placeholder-neutral-400"
    placeholder=" (예시) 01034567890"
  />
  <button
    class="block text-center p-2 border border-gray-300 rounded-md h-14 text-sm text-gray-400 font-bold flex items-center justify-center"
  >
    인증번호 받기
  </button>
</div>

<div class="px-4 mt-2">
  <input
    type="text"
    class="w-full h-14 border-gray-300 rounded-md font-bold  placeholder-neutral-400 peer"
    placeholder=" 인증번호를 입력해 주세요."
  />
</div>

<label for="" class="px-4 mt-4 text-sm font-bold block text-gray-500 mb-2"
  >이메일</label
>
<div class="px-4">
  <input
    type="text"
    class="w-full  h-14 border-gray-300 rounded-md  placeholder-neutral-400 peer"
    placeholder=" 이메일을 입력해주세요."
  />
</div>

<div class="px-4">
  <div class="flex items-center mt-3 mb-2 pb-2 border-b border-gray-300">
    <input
      class="h-5 w-5 mr-2 border-2 border-gray-400 bg-white rounded-md checked:bg-gray-800 checked:border-gray-800 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left cursor-pointer"
      type="checkbox"
      value=""
      id="all"
    />
    <label class="inline-block text-black font-bold" for="all">
      전체 동의
    </label>
  </div>
</div>

<div class="flex justify-between items-center mt-1 text-sm form-check px-4">
  <div>
    <input
      class="h-5 w-5 mr-2 border-2 border-gray-400 rounded-md bg-white checked:bg-gray-800 checked:border-gray-800 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left cursor-pointer"
      type="checkbox"
      value=""
      id="agree1"
    />
    <label class="inline-block text-gray-400 font-bold" for="agree1">
      개인정보 수집 및 이용 동의(필수)
    </label>
  </div>
  <a href="/clause" class="text-gray-500 text-xs mr-3">자세히</a>
</div>
<div
  class="flex justify-between items-center mt-1 text-sm form-check px-4 pb-20"
>
  <div>
    <input
      class="h-5 w-5 border-2 mr-2 border-gray-400 rounded-md bg-white checked:bg-gray-800 checked:border-gray-800 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left cursor-pointer"
      type="checkbox"
      value=""
      id="agree2"
    />
    <label class="inline-block text-gray-400 font-bold" for="agree2">
      이벤트 소식 등 알림 정보 받기
    </label>
  </div>
  <a href="/clause" class="text-gray-500 text-xs mr-3">자세히</a>
</div>

<div class="sticky bottom-0 left-0 right-0 mx-4 pb-4 bg-white ">
  <button
    class="block text-center w-full rounded-full bg-gray-300 rounded h-10 text-sm text-gray-600 flex items-center justify-center"
    >회원가입하기</button
  >
</div>
