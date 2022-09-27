# [rsschool-cv](https://github.com/NinaLisitsyna.io/rsschool-cv/) 
---

![ my_photo ](/photo.jpg)


 # **Nina Lisitsyna**

 ### Junior Front-end developer

 ---

 ### Contact information:

> #### E-mail: lisitsyna.nina87@gmail.com
> #### GitHub: [NinaLisitsyna](https://github.com/NinaLisitsyna)
> #### LinkedIn: [Nina Lisitsyna](https://www.linkedin.com/in/nina-lisitsyna/)
> #### Discord: [Nina_L]()
> #### Telegram: [@Nina_Lisitsyna](https://t.me/+4915733918022)

---

## About me:
Three years ago a new period in my life began when I moved to Berlin. To work here in my profession, I would have had to spend too much time retraining. Then I decided that this was a chance to find a new and interesting specialty. In February 2021, I completed the JS Full-stack course. Now I want to develop more in Front-end. And in order to improve my knowledge and development skills, I am taking training at the RS School. I believe that I can really work as a Front-end developer and be a useful employee for the company.

---


## Education and courses: 

#### _USU named after A.M.Gorky_
**Bachelor´s degree, Filology**
_Sept 2005 - June 2010_

#### _Tel-ran, Educational Center_
**Full-stack Web Development** 
_May 2021 - Feb 2022_

#### _RS School Course "JavaScript/Front-end"_
_In process_

___

## Skills: 

* _HTML_
* _CSS_   
  * _(Preprocessors. SASS)_
* _JavaScript_
  * _React_
  * _Redux_
  * _Node.js_
* _Git_  
* _GitHub_
* _Docker_  
* _MySQL_
* _MongoDB_
* _VS Code_, _Intellij IDEA_ 

___

## Code example: 

```
const Users = () =>{
    const dispatch = useDispatch();
    const users = useSelector (state => state.users)

    useEffect(() =>{
        dispatch (addUserList())
    })

    const renderUsers = () =>{
        return !users.length ? (<p>No available users</p>) : users.map (user => <User key = {user.id} user = {user} /> )
    }
    return(
        <div className='usersList'>
            {renderUsers()}
        </div>
    )

}

export default Users;

```
___

## Languages:

* English B1
* German A1
* Russian (native)

