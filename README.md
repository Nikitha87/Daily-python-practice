def display_personal_info():
    print("please enter your personal information")
    name = input("Name:")
    address = input("Full Address:")
    mobile_number = input("Mobile Number:")
    college_name = input("College Name:")
    course_subjects = []
    print("\nCourse Subjects(enter 'done' when finished):")
    while True:
        subject = input("Subject: ")
        if subject.lower() == 'done':
            break
        course_subjects.append(subject)
        

    print("\npersonal Information:")
    print(f"Name:{name}")
    print(f"Full Address:{address}")
    print(f"Mobile Number:{mobile_number}")
    print(f"College Name:{college_name}")
    print("Course Subjects:")
    for subject in course_subjects:
        print(f"- {subject}")
display_personal_info()

OUTPUT IS THE FORM OF:
please enter your personal information
Name: nikki
Full Address: hyd
Mobile Number: 9000880512
College Name: swomens college

Course Subjects(enter 'done' when finished):
Subject:  python
Subject:  OR
Subject:  Os
Subject:  dbms
Subject:  machine learning
Subject:  done

personal Information:
Name:nikki
Full Address:hyd
Mobile Number:9000880512
College Name:swomens college
Course Subjects:
- python
- OR
- Os
- dbms
- machine learning
