1. Alexey Shmelkov
2.  * __Email:__ alexey.shmelkov@gmail.com
    * ___Skype:__ alexey.shmelkov@gmail.com
    * __Telegram:__ @z0mbee
3. 
    In the modern world, it`s difficult to find truly high-quality and intuitive software. When you find a site or application without a overloaded interface and advertising, it immediately becomes pleasant to your soul, as before when the Internet just appeared and you explored its open spaces. 
    I want to return this feeling of nostalgia to myself and others.

4.  Programming languages: 
        * Python - basic
        * JS - basic
        * C# - low
        * Java - low
    Frameworks: 
        * Selenium
        * PyTest
        * Mocha
    Methodologies:
        * Unit testing
        * PageObject model
        * CI/CD
        * Agile (Scrum, Kanban)
    Version control:
        * Git
    Tools:
        * Jira
        * Bamboo
        * BitBucket
        * Confluence

5. The function gets tweet find hashtags into it and return to you clear hashtags without '#' symbol.
```javascript
var getHashTags = function (tweet) {
    
    var hashTags = tweet.split(' ').filter(isHashTagExist)
    var clearedHashTags = []
    
    hashTags.forEach(clearHashtag)

    function isHashTagExist(word) {
        return word.startsWith('#')
    }

    function clearHashtag (item) {
        if (item.length > 1) {
            clearedHashTags.push(item.slice(1))
        }
    }

    return clearedHashTags
    };
```
6.  Experience:
    I have been working in IT for almost 7 years now.
    * Started with an engineer to set up and repair a computers and related equipment.
    * Then I worked as an assistant of administrator of IT.
    * Then I got a job as implementation engineer of software for a CCTV development company.
    * In the same company I became a manual QA, but it quickly got tired and I began to study automated testing.
    * At the next company, I've been as a full stack QA (manual + automated). We test the web application, which developed on React/Redux stack.
    At the moment I want to become a front-end (maybe full stack) web developer and do my best to achieve this goal.

7. Education (including courses, seminars, lectures, online learning)
    Higher education:
        University: Moscow government industrial university (MGIU)
        Faculty: Economics, Management and Information Technology
        Specialization: Organization and technology of information security/protection
    Additional education:
        Course: [Software-testing](http://Software-testing.ru), 'Intensive course for beginner QA'
        Practice book: 'Head First JavaScript Programming'
        Interactive book: [LearnJavascript](http://learnJavascript.ru) (in progress)

8. Started practice on [SkyEng](http://skyeng.ru/) with pre Intermediate level about 1 year ago. At now continue education with Intermediate level.