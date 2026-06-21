# Database Design

## Exam

| Field | Type |
|---------|---------|
| title | string |
| description | string |
| role | enum |
| time_per_question | number |
| overall_time_limit | number |
| is_published | boolean |

---

## Question

| Field | Type |
|---------|---------|
| exam_id | string |
| question_text | string |
| options | array |
| correct_option_id | string |

---

## ExamAttempt

| Field | Type |
|---------|---------|
| candidate_name | string |
| candidate_email | string |
| employee_id | string |
| score | number |
| percentage | number |
| status | enum |
| remarks | string |
| violation_screenshot_url | string |
