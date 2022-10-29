# G_programming_report_web

---

## 변경점

#### 사용 Framework

- Bootstrap
- bulma
- foundation

#### Framework 적용

- Bootstrap
  - align-items-center, row , col, w-25
  ```html
  <section id="my_info" class="message is-dark row align-items-center">
    <!---->
    <h2 class="message-header">My info</h2>
    <img src="images/profile.jpg" alt="홍길동의 얼굴 사진" class="w-25" />
    <table class="col ">
      ...
    </table>
  </section>
  ```
  - table-warning, fs-2
  ```html
  <table class="table-warning">
    <tbody>
      <tr>
        <th class="fs-2">이름</th>
        <td class="fs-2">홍길동</td>
      </tr>
      <tr>
        <th class="fs-2">직업</th>
        <td class="fs-2">개발자</td>
      </tr>
      <tr>
        <th class="fs-2">나이</th>
        <td class="fs-2">38</td>
      </tr>
      <tr>
        <th class="fs-2">거주지</th>
        <td class="fs-2">부산</td>
      </tr>
    </tbody>
  </table>
  ```
- Bulma
  - message is-warning, message-header, message-body
  ```html
  <section id="" about class="message is-warning">
    <h2 class="message-header">About</h2>
    <p class="message-body">개발자가 되어서 다 패버릴거야...</p>
  </section>
  ```
- foundation
  - thumbnail
  ```html
  <img
    src="images/profile.jpg"
    alt="홍길동의 얼굴 사진"
    class="col thumbnail"
  />
  ```

## 사이트 주소

- github.io :
- netlify
