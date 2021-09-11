# Hordyna Dmytro
## Frontend Developer

>_When I studied at university, I had internship abroad and traveled. I saw that Europe was many times more technologically advanced than my country, and there I began to learn and fall in love programming._

![My foto](/Iam.jpeg)


---
### 1.  Contactact Info
 1. **Email:** *[dim4ka2013@gmail.com](mailto:dim4ka2013@gmail.com)*
 2. **Phone:** *+380937587549*
 3. **Telegram:** *[@dmitry_hordyna](https://t.me/dmitry_hordyna)*
---
### 2. Skills
 - _HTML_
 - _CSS_
  - _SASS_
  - _JS_
 - _REACT_
---### 3. Experience

Now I'm student in GoIt school.

More than 10 prject since 2020 year,and also 3 team project.Latest:

- [ice-cream_SHOP](art-smirnov.github.io/team-project/)
- [soundTeka](art-smirnov.github.io/team-project-js/)
- [Filmoteka](https://dh-netlify-tutorial.netlify.app/)
- [Barber_shop](https://dmitryhordyna.github.io/Template_Barber-Shop/)
- [JS_and_more](https://dmitryhordyna.github.io/GoIT_Api-Timer-ChangeTheme/)
- [Founder](https://dmitryhordyna.github.io/GoIT_Finder/)

<details>
 <summary>Code examples</summary>
 <pre>
//module
import { combineReducers } from 'redux';
import { createReducer } from '@reduxjs/toolkit';
//component
import actions from './action_phonebook';
import dataContacts from '../../data/data.json';

const items = createReducer(dataContacts, {
  [actions.addContact]: (state, { payload }) => foundMatch(state, payload),
  [actions.deleteContact]: (state, { payload }) =>
    state.filter(({ id }) => id !== payload),
});

const filter = createReducer('', {
  [actions.filterContact]: (_, { payload }) => payload,
});

function foundMatch(allContacts, newContact) {
  const chek = allContacts.some(
    ({ name, number }) =>
      name === newContact.name || number === newContact.number,
  );
  if (chek) {
    alert(`You have this number or name!!!Sorry try again.`);
    return allContacts;
  } else {
    return [newContact, ...allContacts];
  }
}

export default combineReducers({
  items,
  filter,
});
  </pre>
</details>

--- 
### 4. Education
---
 #### _NULES 2013-2018_
> - _Bachelor's degree | Design engineer_
 > - _Master's degree | Design engineer_
---
### 5. English level

_Intermediate(B1)_
- Now I'm student in Speak Up school
 ---

