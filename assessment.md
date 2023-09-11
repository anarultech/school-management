> স্কুল মানাজেমেন্ট প্রোজেক্ট

- [ ] Institute
  - [ ] name
  - [ ] established_year
  - [ ] president
  - [ ] principal
  - [ ] sub_domain
  - [ ] email
  - [ ] address
  - [ ] phone_number_1
  - [ ] phone_number_2
  - [ ] image
  - [ ] logo
  - [ ] description
  - [ ] eiin_number
  - [ ] institute_code
  - [ ] types
- [ ] Klass
  - [ ] name
  - [ ] seats
  - [ ] room_number
- [ ] Subjects
  - [ ] name
  - [ ] code 
  - [ ] option [OPTIONAL, MANDATORY]
  - [ ] type [Primary, Secondary]
- [ ] Users
  - [ ] user
    - [ ] unique_user_id
    - [ ] fist_name
    - [ ] last_name
    - [ ] username
    - [ ] email
    - [ ] phone_number
    - [ ] age
    - [ ] gender
    - [ ] address
    - [ ] role []
    - [ ] blood_group
    - [ ] status [Active, Inactive]
  - [ ] Students Profile
    - [ ] user
    - [ ] sessions []
    - [ ] passport_size_image
    - [ ] father_name
    - [ ] mother_name
    - [ ] father_or_mother_mobile_number
    - [ ] blood_group
    - [ ] badge
  - [ ] Assistant Head Teacher
    - [ ] father_name
    - [ ] mother_name
    - [ ] passport_size_image
    - [ ] subjects
    - [ ] grade
    - [ ] salary
    - [ ] mobile_numbers
  - [ ] Committee
  - [ ] Assistant Teacher
  - [ ] Office Assistant
  - [ ] office_staff

- [ ] Degree
  - [ ] teacher_profile
  - [ ] choices
  - [ ] point
  - [ ] certificate
  - [ ] session_year

- [ ] Library
  - [ ] Books
    - [ ] writer name
    - [ ] name
    - [ ] cover_image
    - [ ] pdf_file
    - [ ] page_number
    - [ ] prokasoni
- [ ] Attendance
  - [ ] user
  - [ ] entry_date_time
  - [ ] leave_date_time
  - [ ] status
- [ ] Session year
  - [ ] Klass
  - [ ] students []
  - [ ] years
- [ ] Exam
  - [ ] student
  - [ ] exam_type [1st exam, 2 exam, final_exam, test_exam]
  - [ ] session_year
  - [ ] fees
  - [ ] total_points
  - [ ] status [FAIL, PASS]
- [ ] Exam Subjects
  - [ ] exam
  - [ ] student
  - [ ] point
  - [ ] subject
  - [ ] status [ABSEND, PRESENT]
- [ ] Assignment
  - [ ] session_year
  - [ ] student
  - [ ] subject
  - [ ] lessions
  - [ ] point
  - [ ] teacher
  - [ ] status [complete, incomple]
- [ ] Rutine
  - [ ] session_year
  - [ ] klass
  - [ ] subject
  - [ ] time
  - [ ] teacher
  - [ ] department[generale, since]
- [ ] Events
  - [ ] name
  - [ ] banner
  - [ ] group_image
  - [ ] date
  - [ ] bugest
  - [ ] cost
- [ ] Settings
  - [ ] 
- [ ] Fees
  - [ ] choices[exam, event, monthly]
  - [ ] amount
  - [ ] content_type
  - [ ] object_id
  - [ ] content_object[content_type, object_id]
  - [ ] status[paid, due]
- [ ] Address
  - [ ] Country
  - [ ] Division
  - [ ] District
  - [ ] sub_district
  - [ ] union
  - [ ] word
  - [ ] moholla
  - [ ] house_number | optional
  - [ ] road_number | optional

- [ ] ছাত্র
- [ ] গার্জিয়ান
- [ ] প্রধান শিক্ষক
- [ ] সহকারী প্রধান শিক্ষক
- [ ] সহকারী শিক্ষক
- [ ] দপ্তরি
- [ ] অফিস সহকারী
- [ ] পিয়ন
- [ ] কেরানি

> ছাত্র, শিক্ষক প্রতিদিন হাজিরা
- [ ] ছাত্র, শিক্ষক প্রতিদিন প্রতিষ্ঠানে প্রবেশ করেই হাজিরা দিবেন
- [ ] ছাত্র, শিক্ষক প্রতিদিন প্রতিষ্ঠানে থেকে বের হবার সময় আবার হাজিরা দিতে হবে
- [ ] যদি ছাত্র বা শিক্ষক ১০টার মধ্যে হাজিরা না দেন তাহলে ছাত্রের বেলায় তার গার্জিয়ানের মোবাইল একটা  মেসেজ যাবে আর শিক্ষকের বেলায় অফিস সহকারী বা করতিপক্কর কাছে একটা মেসেজ যাবে আর তার ছাত্রদের কাছে ও একটা মেসেজ যাবে এবং তার পরিবর্তে কে তাদের ক্লাস নিবে সেটা অফিস করতিপক্ষ জানিয়ে দিবেন

> ক্লাস রুম নাম
- [ ] ১ম শ্রেণির
- [ ] ২য় শ্রেণির
- [ ] ৩য় শ্রেণির
- [ ] ৪য় শ্রেণির
- [ ] ৫ম শ্রেণির

> সাবজেক্ট
- [ ] বাংলা
- [ ] ইংরেজি
- [ ] অংক

> সেশন বছর
- [ ] ক্লাসঃ FK
- [ ] সাবজেক্টঃ []
- [ ] ছাত্রঃ []

