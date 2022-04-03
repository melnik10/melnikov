Melnikov Vladislav
===============================================

***********************************************

### 1. Contacts

* vladislavxperiaz3@gmail.com
* vaMuller (Telegram)
* melnik10#1735 (Discrod)

### 2. About myself:

My firstname is Vladislav. I live in Kaliningrad. 

### 3. Skills:
* HTML
* CSS (SCSS)
* JS (ES6)
* REST
* Git
* npm/yarn
* webpack (base)
* React
* Redux(toolkit - base)
* Mobx
* TypeScript
* NodeJS(base)
* PostgreSQL, MongoDB(base)
* Express (base)


### 4. Code example
```
export const ConfirmForm = (props) => {
    const [code, setCode] = useState(props.code)
    useEffect(() => {
        alert('Ваш код для входа: ' + code)
    }, [code])
    return (
      <div>
          <form onSubmit={props.handleSubmit}>
              <div><Field className={style.input} name='confirmCode' component={InputField} type='number'  placeholder='Input code...'/></div>
              <div className={style.sendCode} onClick={() => {
                  let newCode = props.getRandomCode(100000, 1000000)
                  setCode(newCode)
                  props.setConfirmCode(newCode)
              }
              }>Send the code again?
              </div>
              <button className={style.button} type={'submit'}>Send code</button>
              <div className={style.errorContainer}><div className={style.error}>{props.error}</div></div>
          </form>
      </div>
    )
}
```

### 5. My works:
1. [Pokemon (React)](https://melnik10.github.io/pokemon-code/#/app)
    Login: kode@kode.ru, password: Enk0deng
2. [Paint-Online (Websocket) (React/NodeJS)](https://melnik10.github.io/paint-websocket/#/)
3. [Cloud-space (React/NodeJS)](https://cloud-mern.herokuapp.com/login)

### 6.Education:
1. Radio engineer (2019)
2. QT/C++ (2017-2020)
3. HTML, CSS, GIT on YouTube
4. JS - [https://learn.javascript.ru](https://learn.javascript.ru)
5. [Путь самурая 1.0 - 2.0](https://www.youtube.com/watch?v=gb7gMluAeao&list=PLcvhF2Wqh7DNVy1OCUpG3i5lyxyBWhGZ8)
6. TypeScript, Redux-toolkit, MobX (youtube, documentation)

### 7. Language
1. Russian - native
2. English - A1+