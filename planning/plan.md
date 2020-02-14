<h1>Planning</h1>

[Go to back](../README.md)

## target market : korea

## 공공도서관 현황

<img width="516px" height="195px" src="../img/libaraynumber.jpg">

## website name: ???(Will Update later)

## Main Users: Korean

## Feature

- Log In/Sign Up (로그인 / 회원가입 기능구현)
- \*! if User Login ==> \*\*Log Out\*\*

---

- Social Login (소셜로그인 기능)
  - KaKaoTalk Login
  - Facebook Login

---

- **! List** (책 리스트 구현) : 중복 모델 사용
  - book img
  - book title
  - book author
  - book publisher
  - book Publish year
  - book status
    - Want to Read / Reading / Already read

---

- Book Detail
  - book img
  - book title
  - book subtitle (required="false" )
  - book status
    - Want to Read / Reading / Already read
    - Rating
  - Rating List
    - Follower Rating
    - Public Rating
    - library(교보문고, 알리딘, 쿠팡...) Rating
  - Recommend **Post Search(User name)**
    - Total : Number
      - link(User List)
        - Profile img
        - User name
        - Follow Button
  - **KoReaders** SNS (like instagram) (privacy)
    - (My/public ==> Essay or Story)
  - Book Info
    - API
    - Store link
  - Book Category
  - Book description
  - Book description by Author
  - Author description

---

- Recommend Admin Pick List (추천글 기능: public)
  - defalut: admin pick

---

- Story Upload (privacy)
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

- Essay Upload (privacy)
  - img X
    - book O (tage)
      - public/privacy/follower
        - title
        - context

---

- Search (검색기능) (public)
  - total --> List
  - book --> List
  - groupe
  - story --> **?** SNS (like instagram) (privacy)
    - (Story or Essay Upload context)
  - user name ---> **Post Search(User name)**
    - X Follow Button

---

- **?** SNS (like instagram) (privacy)

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

- Book Mark Detail
  - **! List** (책 리스트 구현) : 중복 모델 사용
    - X book status
    - Add my feed Number
      - logic: link Book Mark Detail --> Get My Feed
    - feature: 단어별 정렬기능

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

- group Join

  - ???(Will Update later)

- grup Delete
  - ???(Will Update later)

---

- User Detail (privacy)
  - Friend Search (facebook/kakaotalk api)
  - follower/ followering number
  - **! if Get Other User Detail ==> Follow Button**
  - User name
  - Profile img
  - List View (number)
    - book
    - collections
    - story (Story Upload context)
    - Essay (Essay Upload context)
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
        - Post User Detail > List View > book
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
  - 1 : 1 Talk (고객센터)
    - 24hours...
    - Call Button (post admin email)
  - Find User
    - Search
      - logic: **Post Search(User name)** -> Get User Detail (if User Public setting Ok!)
  - Update Request
    - Udate request Title & Context
    - Request List
    - Updating List
    - Updated List
    - Request Button
  - Legal Notice
  - **Log Out**

---

### Will update later

#### version 1.0.0

- Log In/Sign Up (로그인 / 회원가입 기능구현)
- Social Login (소셜로그인 기능)
- List
- Recommend Admin Pick List (추천글 기능: public)
- SNS (like instagram) (privacy)
- Search (검색기능) (public)
- group (like facebook group)
- User Page
- Setting

#### version 1.0.1

- header change (Join/LogIn ---> LogOut)
- List : 중복 모델 지정
- Book Detail
- Delete Upload Name
- Create Story Upload
- Create Essay Upload
- Search logic
- Book Detail
- group Join
- Change Name User Detail && new Upload Feature
- 1 : 1 Talk (고객센터)
- Find User
- Update Request
- Legal Notice
- LogOut
