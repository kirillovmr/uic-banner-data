# LocalClassDataStorage

total 469749 classes

Each file:
```
{
    termCode: string,
    termDescription: string,
    totalNumberOfClasses: number,
    timestamp: Date.now(),
    timeCreated: (new Date()).toString(),
    classes: ClassData[] #see below
}
```

ClassData:
```
{
    "id": 2245526,
    "term": "220188",
    "termDesc": "Fall 2018 - Chicago",
    "courseReferenceNumber": "10630",
    "partOfTerm": "1",
    "courseNumber": "107",
    "subject": "CS",
    "subjectDescription": "Computer Science",
    "sequenceNumber": "AB1",
    "campusDescription": "Chicago",
    "instructionalMethodDescription": null,
    "scheduleTypeDescription": "Laboratory",
    "courseTitle": "Introduction to Computing and Programming",
    "creditHours": 0,
    "maximumEnrollment": 24,
    "enrollment": 16,
    "seatsAvailable": 8,
    "waitCapacity": 0,
    "waitCount": 0,
    "waitAvailable": 0,
    "crossList": null,
    "crossListCapacity": null,
    "crossListCount": null,
    "crossListAvailable": null,
    "creditHourHigh": 4,
    "creditHourLow": 0,
    "creditHourIndicator": "OR",
    "openSection": true,
    "linkIdentifier": "AB",
    "isSectionLinked": true,
    "subjectCourse": "CS107",
    "faculty": [
        {
            "bannerId": "11722",
            "category": null,
            "class": "net.hedtech.banner.student.faculty.FacultyResultDecorator",
            "courseReferenceNumber": "10630",
            "displayName": "Reckinger, Scott",
            "emailAddress": "scotreck@uic.edu",
            "primaryIndicator": false,
            "term": "220188"
        },
        {
            "bannerId": "11723",
            "category": null,
            "class": "net.hedtech.banner.student.faculty.FacultyResultDecorator",
            "courseReferenceNumber": "10630",
            "displayName": "Shah, Rushit",
            "emailAddress": "rshah231@uic.edu",
            "primaryIndicator": true,
            "term": "220188"
        }
    ],
    "meetingsFaculty": [
        {
            "category": "01",
            "class": "net.hedtech.banner.student.schedule.SectionSessionDecorator",
            "courseReferenceNumber": "10630",
            "faculty": [

            ],
            "meetingTime": {
                "beginTime": "0800",
                "building": "2SEL",
                "buildingDescription": "Science &amp; Engr Laboratory",
                "campus": "200",
                "campusDescription": "Chicago",
                "category": "01",
                "class": "net.hedtech.banner.general.overall.MeetingTimeDecorator",
                "courseReferenceNumber": "10630",
                "creditHourSession": 0.0,
                "endDate": "12/07/2018",
                "endTime": "0850",
                "friday": false,
                "hoursWeek": 1.0,
                "meetingScheduleType": "LAB",
                "meetingType": "CLAS",
                "meetingTypeDescription": "Class",
                "monday": true,
                "room": "2249F",
                "saturday": false,
                "startDate": "08/27/2018",
                "sunday": false,
                "term": "220188",
                "thursday": false,
                "tuesday": false,
                "wednesday": false
            },
            "term": "220188"
        }
    ],
    "reservedSeatSummary": null,
    "sectionAttributes": null
},
```
