Melnikov Vladislav
===============================================

***********************************************

### 1. Contacts

* vladislavxperiaz3@gmail.com
* vaMuller (Telegram)
* melnik10#1735 (Discrod)

### 2. About myself:
My firstname is Vladislav. I live in Kaliningrad. I'm a frontend developer at [Selsup](selsup.ru)!

### 3. Skills:
* HTML
* CSS (SCSS)
* JS
* TypeScript
* React
* Redux (toolkit, saga - base)
* Leaflet
* Amcharts
* Git
* NodeJS (base)
* Webpack (base)


### 4. Code example
```
return (
        <div className={style.Block}>
            {
                React.Children.toArray(props?.children).map((child, index) => {
                    if (index === reactChildCount - 1) {
                        return null
                    }
                    return (
                        <React.Fragment key={index}>
                            <div className={style.Resizable}
                                 ref={div => div && (resizableElementsRef.current[index] = {current: div})}
                            >
                                {child}
                            </div>
                            <div className={style.Draggable}
                                 style={{cursor: 'col-resize'}}
                                 draggable={"true"}
                                 onDragStart={(e) => {
                                     e.dataTransfer.dropEffect = 'link'
                                     initial(e.clientX, index)
                                     dispatch(setIsResizeMap(true))
                                 }}
                                 onDragEnd={() => {
                                     dispatch(setIsResizeMap(false))
                                 }}
                                 onDrag={(e) => {
                                     e.dataTransfer.dropEffect = 'link'
                                     resize(e.clientX, index)
                                 }}
                                 onDragOverCapture={(e) => {
                                     e.dataTransfer.dropEffect = 'link'
                                 }}
                            />
                        </React.Fragment>
                    )
                })
            }
            <div className={style.OtherContent}> {React.Children.toArray(props.children).at(-1)} </div>
        </div>
    );
```

### 5. My works:
1. [Pokemon (React)](https://melnik10.github.io/pokemon-code/#/app) Login: kode@kode.ru, password: Enk0deng
2. [Paint-Online (Websocket) (React/NodeJS)](https://melnik10.github.io/paint-websocket/#/)
3. [Cloud-space (React/NodeJS)](https://cloud-mern.herokuapp.com/login)

### 6.Education:
1. Radio engineer (2019)
2. QT/C++ (2017-2020)
3. HTML, CSS, GIT on YouTube
4. JS - [https://learn.javascript.ru](https://learn.javascript.ru)
5. [Путь самурая 1.0 - 2.0](https://www.youtube.com/watch?v=gb7gMluAeao&list=PLcvhF2Wqh7DNVy1OCUpG3i5lyxyBWhGZ8)

### 7. Language
1. Russian - native
2. English - A1+