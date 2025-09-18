#Personal Information
full_name = "Ryleigh Butler"
student_email = "rgbutler@ncat.edu"
hometown = "Pearl, MS"
graduation_semester = "Spring 2029"
major = "Computer Engineering"

#Academic Data
current_courses = ["COMP 163", "MATH 131", "GEEN 100", "ECEN 101", "GEEN 111", "HIST 103"]
completed_courses = [""]
credit_hours = [3, 4, 2, 3, 1, 3]
gpa_history = [""]

#Contact Information Storage
emergency_contact = ("Mom", "Genia Butler", "704-555-0199")
home_address = ("120 Eva Drive", {hometown}, "39208")
instagram = ("Instagram", "@ilu.vryx", 586)
twitter = ("Twitter", "@doesnotexist", 127 )
birthday = ("Birthday", 7, 3, 2007)

#Interest Tracking
current_skills = {"Python basics", "Creativity", "Problem Solving", "Time management", "Photography"}
skills_to_learn = {"JavaScript", "Data structures", "Git", "Web design"}
career_interests = {"Software development", "Web development", "Data science", "Game development"}
hobbies = {"Gaming", "Photography", "Reading", "Volleyball", "Music"}
entertainment_backlog = {"Flash", "Business Proposal", "YouTube"}

#Organizational Mapping
course_credits = {
    "COMP 163": 3,
    "MATH 131": 4,
    "GEEN 100": 2,
    "ECEN 101": 3,
    "GEEN 100": 1,
    "HIST 103": 3
}
course_professors = {
    "COMP 163": "Prof. Rhodes",
    "MATH 131": "Dr. Deeb",
    "GEEN 100": "Dr. Knisley",
    "ECEN 101": "Dr. Horne",
    "GEEN 111": "Dr. Parrish",
    "HIST 103": "Dr. Smith"
}
course_rooms = {
    "COMP 163": "Gibbs 337",
    "MATH 131": "Marteena 214",
    "GEEN 100": "Graham 208",
    "ECEN 101": "McNair 240",
    "GEEN 111": "McNair 240",
    "HIST 103": "Online"
}
monthly_budget = {
    "Food": 200,
    "Entertainment": 100,
    "Books": 50,
    "Transportation": 75
}
study_hours_per_subject = {
    "Programming": 25,
    "Math": 8,
    "History": 2
}
contact_directory = {
    "Mom": "704-555-0199",
    "Roommate": "336-555-7821",
    "Academic Advisor": "336-334-5000"
}

#Required Calculations
total_current_credits = credit_hours[0] + credit_hours[1] + credit_hours[2] + credit_hours[3]
total_current_courses = len(current_courses)
total_gpa = gpa_history[0] + gpa_history[1] + gpa_history[2] + gpa_history[3]
cumulative_gpa = total_gpa / total_current_courses
count_completed_courses = len(completed_courses)
total_weekly_study_hours = study_hours_per_subject["Programming"] + study_hours_per_subject["Math"] + study_hours_per_subject["English"] + study_hours_per_subject["History"]
academic_load = total_current_credits + total_weekly_study_hours
monthly_budget_total = monthly_budget["Food"] + monthly_budget["Entertainment"] + monthly_budget["Books"] + monthly_budget["Transportation"]
daily_food_budget = monthly_budget["Food"] / 30
annual_budget_projection = monthly_budget_total * 12
study_cost_per_hour = monthly_budget["Books"] / total_weekly_study_hours

#added values
comp_course = current_courses[0]
comp_credit = course_credits["COMP 163"]
comp_professor = course_professors["COMP 163"]
comp_room = course_rooms["COMP 163"]
math_course = current_courses[1]
math_credit = course_credits["MATH 150"]
math_professor = course_professors["MATH 150"]
math_room = course_rooms["MATH 150"]
eng_course = current_courses[2]
eng_credit = course_credits["ENG 101"]
eng_professor = course_professors["ENG 101"]
eng_room = course_rooms["ENG 101"]
his_course = current_courses[3]
his_credit = course_credits["HIS 105"]
his_professor = course_professors["HIS 105"]
his_room = course_rooms["HIS 105"]
num_monthly_budget = monthly_budget["Food"] + monthly_budget["Entertainment"] + monthly_budget["Books"] + monthly_budget["Transportation"]
food_budget = monthly_budget["Food"]
entertainment_budget = monthly_budget["Entertainment"]
books_budget = monthly_budget["Books"]
transportation_budget = monthly_budget["Transportation"]
contact_name = emergency_contact[1]
contact_relation = emergency_contact[0]
contact_number = emergency_contact[2]
hobbies_count = len(hobbies)


#Analytics Calculations
total_social_media_followers = instagram[2] + twitter[2]
current_skill_count = len(current_skills)
skills_to_learn_count = len(skills_to_learn)
contact_directory_count = len(contact_directory)
entertainment_backlog_count = len(entertainment_backlog)
#academic load is already in the required calculations
equals = ("=" * 64)
spaces = (" " * 13)

print(equals)
print(spaces, "PERSONAL ACADEMIC & LIFE PORTFOLIO")
print(equals)
print(f"Student: {full_name} | Email: {student_email}\nFrom: {hometown} | Graduating: {graduation_semester}\nMajor: {major}")
print()
print("=== ACADEMIC PROFILE ===")
print(f"Current Semester: {total_current_credits} credits across {total_current_courses} courses")
print(f"Cumulative GPA: {cumulative_gpa:.2f}")
print(f"Weekly Study Time: {total_weekly_study_hours} hours")
print(f"Academic Investment: ${study_cost_per_hour:.1f} per study hour")
print()
print(f"Current Courses:")
print(f"{comp_course} - {comp_credit} credits - {comp_professor} - {comp_room}")
print(f"{math_course} - {math_credit} credits - {math_professor} - {math_room}")
print(f"{eng_course} - {eng_credit} credits - {eng_professor} - {eng_room}")
print(f"{his_course} - {his_credit} credits - {his_professor} - {his_room}")
print()
print("=== PERSONAL DEVELOPMENT ===")
print(f"Current Skills: {current_skills}")
print(f"Learning Goals: {skills_to_learn}")
print(f"Career Interests: {career_interests}")
print(f"Skills Currently Have: {current_skill_count}")
print(f"Skills Want to Learn: {skills_to_learn_count}")
print()
print("=== FINANCIAL OVERVIEW ===")
print(f"Monthly Budget: ${num_monthly_budget}")
print(f"Food: ${food_budget} (${daily_food_budget:.1f}/day)")
print(f"Entertainment: ${entertainment_budget}")
print(f"Books: ${books_budget}")
print(f"Transportation: ${transportation_budget}")
print(f"Annual Projection: ${annual_budget_projection}")
print()
print(f"=== CONNECTIONS & CONTACTS ===")
print(f"Emergency Contact: {contact_name} ({contact_relation}) - {contact_number}")
print(f"Home Address: 456 Oak Street, {hometown} 28202")
print(f"Social Media Presence: {total_social_media_followers} followers across 2 platforms")
print(f"Key Contacts: {contact_directory_count} people in directory")
print()
print("=== LIFE STATISTICS ===")
print(f"Total Courses Completed: {count_completed_courses}")
print(f"Current Academic Load: {academic_load} weekly commitments")
print(f"Entertainment Backlog: {entertainment_backlog_count} items")
print(f"Current Hobbies: {hobbies_count} activities")
print(equals)

#DEBUG
#print(type(current_skills))

