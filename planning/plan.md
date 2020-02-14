<h1>Planning</h1>

[Go to back](../README.md)

## target market : korea

## 공공도서관 현황

<img width="516px" height="195px" src="../img/libaraynumber.jpg">

## website name: KoReaders

## Main Users: Korean

## Feature

- Log In/Sign Up (로그인 / 회원가입 기능구현)

---

- Social Login (소셜로그인 기능)
  - KaKaoTalk Login
  - Facebook Login

---

- List (책 리스트 구현)
  - book img
  - book title
  - book author
  - book publisher
  - book Publish year
  - book status
    - Want to Read / Reading / Already read

---

- Recommend Admin Pick List (추천글 기능: public)
  - defalut: admin pick

---

- upload (privacy)
  - img O
    - book O (tage)
      - public/privacy/follower
        - page
        - context
    - book X (tage)
      - public/privacy/follower
        - page
        - context
  - img X
    - book O (tage)
      - public/privacy/follower
        - page
        - context
    - book X (tage)
      - public/privacy/follower
        - page
        - context

---

- Search (검색기능) (public)
  - total
  - book
  - groupe
  - story (upload context)
  - user name

---

- **KoReaders** SNS (like instagram) (privacy)

  - follower
    - default: admin feed
    - feed
  - public
    - feed
  - recomend
    - User Top Rating feed (admin pick)

- SNS feature (public)
  - Like
  - comment
  - book mark

---

- group (like facebook group)

  - group SNS (privacy)
    - feed
    - comments
    - like
    - book mark
  - group Join
  - group Delete

---

- User Page (privacy)
  - Friend Search (facebook/kakaotalk api)
  - follower/ followering number
  - User name
  - Profile img
  - List View (number)
    - book
    - collections
    - story (upload context)
    - book mark
  - User Read Field (view)
    - User name
    - circle graph = Book Keywords Logic (if: book number > 5)
  - `new Date().getFullYear()` READING CHALLENGE
    - I want to read (**number**) : defalut: 0
  - `new Date().getFullYear()` Record number of books read
    - Monthly history graph (number)
  - Read Calender
    - book name
  - Want Book List
    - Want Book Button
      - logic
        - Get Search
        - Post Search
        - Get Book Detail
        - Post Book Detail
        - Post User Page > List View > book
        - get User Detail
    - Book image (view)

---

- Setting

  - Account
    - Default Profile Change
      - Profile img: (default: "")
      - Display name: (default: Join value)
      - About me: (defalut: "")
      - email: kakaotalk/facebook
    - Advance Profile Change (!child public/privacy select)
      - Name: default(Join email name)
      - phone: default(default:"")
      - Date of Birth: year (default: "")
      - Gender(select)
        - F/M (default: "")
      - My interest(select)
        - AI
        - Art
        - Child Care
        - Communication
        - Computer
        - Cooking
        - Data analysis
        - Design
        - Diet
        - Economy / Management
        - Education
        - English
        - Essay
        - Exercise / Leisure
        - Financial Technology
        - habit
        - Health
        - Hobby
        - Humanities
        - Language
        - Literature
        - Marketing
        - Marriage
        - Music
        - Parenting
        - Pet
        - poem
        - Real Estate
        - Self Development
        - Science
        - Society / Politics
        - Startup
        - Travel
        - ect (기타)
    - Delete Account
      - use again ? prompt("thank you") : Delete Account
  - Notification settings (select)
    - sns feature (yes/no)

---

### Will update later
