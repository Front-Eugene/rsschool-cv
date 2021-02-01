## First name: **Eugene** 
## Last Name: **Morozenko**
![Photo](https://sun9-34.userapi.com/impg/o0E91uCHZQV60VADn4BfqZYetQOoThWfbTG-6g/v2SpWsbsfdU.jpg?size=137x140&quality=96&proxy=1&sign=364a8c75f508f641399bd871fabc6c35&type=album)

## Contacts:
- **Minsk**
- **+375257942616**    
- [**Linkedin**](https://www.linkedin.com/in/eugenemorozenko/) 
- [**Github**](https://github.com/Front-Eugene)

## Personal information:
### Eugene, 24 years old. I graduated from BNTU, but realized that it's wasn't my field. I want to learn interesting and popular profession. I've worked in different spheres:

- waiter
- taxi driver
- security guard

### where I manageded to absorb some useful soft skills.
### Now I study HTML, CSS, JavaScript. I hope to find my place in the IT field soon.

```javascript
   
   const deadline = '2021-12-11';

    function getTimeRemaining(endTime) {
        const t = Date.parse(endTime) - Date.parse(new Date()),
              days = Math.floor(t / (1000 * 60 * 60 * 24)),
              hours = Math.floor((t / (1000 * 60 * 60) % 24)),
              minutes = Math.floor((t / 1000 / 60) % 60),
              seconds = Math.floor((t / 1000) % 60);
        return {
            'total': t,
            'days': days,
            'hours': hours,
            'minutes': minutes,
            'seconds': seconds
        };
    }

    function getZero(num) {
        if (num >= 0 && num < 10) {
            return `0${num}`;
        } else {
            return num;
        }
    }

    function setClock(selector, endTime) {
        const timer = document.querySelector(selector),
              days = timer.querySelector('#days'),
              hours = timer.querySelector('#hours'),
              minutes = timer.querySelector('#minutes'),
              seconds = timer.querySelector('#seconds'),
              timeInterval = setInterval(updateClock, 1000);

        updateClock();

        function updateClock() {
            const t = getTimeRemaining(endTime);

            days.innerHTML = getZero(t.days);
            hours.innerHTML = getZero(t.hours);
            minutes.innerHTML = getZero(t.minutes);
            seconds.innerHTML = getZero(t.seconds);

            if (t.total <= 0) {
                clearInterval(timeInterval);
            }
        }
    }

    setClock('.timer', deadline);

```



## Educational courses:
[**Udemy**](https://www.udemy.com/)
- ### WEB-developer 2020
- ### JavaScript + React Course

## English:
### The level of English is approximately A1-A2. I never miss the opportunity to chat with a native speaker. I use the app "Duolingo" in learning English. 
