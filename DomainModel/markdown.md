```mermaid
        
    Dashboard --|> Courses
    History --|> Dashboard
    Inbox --|> Courses
    Groups --|> Courses
    Account --|> Courses


    class Dashboard {
        +announcements()
        +assignments()
        -newAddition()
        +myGrades()
        -bell()
        -view()
        +courses()

    }

    class Account {
        +notifications() 
        -profile()
        +files()
        -settings()
        -qrForMobileLogin()
        +globalAnnouncements()
        -logout()
        -contrastSetting()

    }

    class Courses {
        +courses()
        +comunnity()
        +allCourses()
    
    }

    class Groups {
        +allGroups()

    }

    class Calendar {
        -view()
        -createNewEvent()

    }

    class Indox {
        +courseSelection()
        +inboxCriteria()
        +search()
        +contacts()
        +newMessage()
        -messageOptions()

    }

    class History {
        +course()
        +assignments()
        +announcements()

    }

    class Help {
        -canvasGuide()
        -otherResources()

    }

```