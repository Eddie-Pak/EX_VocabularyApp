# 단어장 앱

단어장 추가 & 삭제

<img src="https://github.com/Eddie-Pak/EX_VocabularyApp/assets/136288531/c1be65c6-09cb-48c1-a946-ea75eb63ae2f" width="300">

단어장 수정

<img src="https://github.com/Eddie-Pak/EX_VocabularyApp/assets/136288531/dca7c4d9-53df-49cd-a6c4-f0049f1cd0b1" width="300">

# 개요

### 구현기능

- 단어장 UI 구현
- 단어 추가
- 단어 수정
- 단어 삭제

---

# 학습 목표

- 데이터를 추가, 수정, 삭제 하고, UI 에 변경된 내용을 보여줄 수 있다
    - Room 을 이용해, 데이터 추가, 수정, 삭제, 읽기
    - RecyclerView 와 RecyclerViewAdapter 를 이용해 리스트 그리기
    - 변경된 데이터에 따른 내용을 UI 업데이트
- UI
    - [RecyclerView, Adapter](https://developer.android.com/guide/topics/ui/layout/recyclerview?hl=ko)
        - [어댑터로 레이아웃 빌드](https://developer.android.com/guide/topics/ui/declaring-layout?hl=ko#AdapterViews)
    - TextInputLayout, TextInputEditText
    - ChipGroup, Chip
    - ConstraintLayout - Barrier
- Kotlin
    - [data class](https://kotlinlang.org/docs/data-classes.html)
- Android
    - [Room](https://developer.android.com/training/data-storage/room?hl=ko)
    - registerForActivityResult
    - Parcelize
    
---

### RecyclerView
![image](https://user-images.githubusercontent.com/24618293/198893552-43289ea1-f225-4cf0-9758-d2674e26926d.png)

### RecyclerViewAdapter
![image](https://user-images.githubusercontent.com/24618293/198893559-5277ea32-7f67-4663-8d2d-522d93733162.png)

# 한걸음 더 
- 강의에서 구현한 방법과 다르게 RecyclerView 아이템 클릭 리스너 구현해보기
- 단어 추가 화면에서, 추가 버튼 클릭 시, 유효성 체크 해보기

- guideLine, Barrier의 차이 알아보기
- FloatingActionButton, ImageView 쓰는 타이밍알아보기
- RecyclerView 복습해보기
- Room 복습해보기
- Parcelable한 데이터, @Parcelize 에 대해 알아보기
  
