# **ВИКТОРИЯ ЮШКЕВИЧ** 
## медицинский физик
## КОНТАКТНАЯ ИНФОРМАЦИЯ
* адрес: аг. Лесной
* телефон: +375 44 755 93 27
* e-mail: yushkevich.ur@gmail.com
## ОБО МНЕ
Работаю медицинским физиком в рнпц онкологии и очень хочу уехать в италию. и удачно выйти замуж. за программиста. чтобы было о чем поговорить расширяю кругозор таким способом.
## НАВЫКИ
* HTML
* CSS
* JS
* ECLIPSE V.13.7 & ECLIPSE V.16.1
* WINDOWS OS
## CODE EXAMPLES
```
import React, {useState, useEffect} from 'react';
import { User } from './components/User';

export const Users = () => {
  const [users, setUsers] = useState([])

  useEffect (() => {
    fetch('https://jsonplaceholder.typicod.com/users')
      .then(response => response.json())
      .then(json => setUsers(json))
  }, [setUsers])


  return <div>
    {
      !users.length && <>Loading...</>
    }
    {
      users.map((user) => <User user={user}/>)
    }
  </div>
}
```
## ОБРАЗОВАНИЕ
* МГЭИ им. А.Д. Сахарова БГУ (бакалавриат + магистратура)
* художественная школа
* незаконченные курсы ИТ
## ИНОСТРАННЫЕ ЯЗЫКИ:
* русский
* английский
* немецкий
* итальянский
