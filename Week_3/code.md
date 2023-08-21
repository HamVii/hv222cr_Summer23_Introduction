 Code block for Exam 3
    
    let age = 30
    let name = 'Hampus V'
    let occupation = 'physio'
    let drinkList = ['gin', ' lemons', ' simple syrup.']
    let semester = 4

    console.log(typeof semester)
    console.log(typeof drinkList)
    console.log(drinkList)

    if (occupation === 'physio'){
    console.log ('Hello ' + name + ', nice to meet you! How old are you?')
    console.log ('I am ' + age + '!')
    }

    console.log ('How old will you be next year?' )
    if (typeof age === 'number'){
    age = 31
    console.log ('I will be ' + age + '.')
    }

    console.log ('You will be studying for ' + semester + ' semesters?')
    if (typeof semester === 'number'){
    semester = 6
    console.log ('Correct, but it could also end up as ' + semester + ' semesters.')
    }