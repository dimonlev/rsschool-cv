# Dmitry Levkovich

---

#### Contacts

- **Mobile:** +375-25-619-11-77
- **E-mail:** dzmitry.liaukovich@gmail.com
- **Telegram:** @ecstas1
- **Discord:** @ecstas1#6769

#### Summary

7 years in sales, 6 years in sales management(include 4 years in Vietnam, work with foreigners)

#### Skills

Good knowledge of HTML, CSS & SCSS, VanillaJS, basic React, Git & GitHub, self-learning basic C#, also interesting and looking for Python.

#### Latest code sample

```
import React from "react";
import Dialog from './Dialog/Dialog';
import Message from './Message/Message';
import { addMessageActionCreate, newMessageOnChangeActionCreate } from "../../redux/messages-reduser";
import Messages from "./Messages";

const MessagesContainer = (props) => {
  let newDialogData = props.messagePage.dialog.map(dialog => <Dialog name={dialog.name} nickName={dialog.nickName} id={dialog.id} />);
  let newMessageData = props.messagePage.message.map(message => <Message text={message.text} id={message.id} date={message.date} />)

  //let newMessageElement = React.createRef(); changed from ref

  let newMessage = () => {
    props.dispatch(addMessageActionCreate())
  }

  let addNewMesage = (event) => {
    let text = event.target.value; // changed from ref
    props.dispatch(newMessageOnChangeActionCreate(text))
  }

  return (
    <Messages newDialogData={newDialogData} newMessageData={newMessageData} newMessage={newMessage} addNewMesage={addNewMesage} messagePage={props.messagePage} />
  );
};

export default MessagesContainer;
```

#### Github

[Github](https://github.com/dimonlev)

#### Experience

A little bit freelancing in some projects, making front-end. But now active finding full-time job as a Junior Web Dev.

#### Education

BELARUSIAN STATE ACADEMY OF COMMUNICATIONS (2007)

#### Soft skills

Work in team, good communications.

#### English

Pre-Intermediate A2+

#### Chinese

Elementary A1

#### Vietnamese

Beginner A0
