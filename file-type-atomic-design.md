# File Type Atomic Design

```
src/
|-- components/
|	 |- atoms/
|  |  |-- Button/
|	 |  |   |-- Button.jsx
|  |- molecules
|  |  |-- ButtonWithInput/
|	 |  |   |-- ButtonWithInput.jsx
|  |- organisms
|  |- templates
|-- contexts/
|   |-- ThemeContext/
|   |   |-- ThemeContext.jsx
|-- hooks/
|   |-- useWindowSize/
|   |   |-- useWindowSize.js
|-- pages/
|   |-- UserProfile/
|   |   |-- components/
|   |   |   |-- SomeUserProfileComponent/
|   |   |   |   |-- SomeUserProfileComponent.jsx
|   |   |-- UserProfile.jsx
|-- routes/
|   |-- routes.jsx
|-- utils/
|   |-- some-util/
|   |   |-- someUtil.js
|-- services/
|   |-- some-service/
|   |   |-- someService.js
|-- store/
|   |-- userStore.js
|   |-- store.js
|-- App.jsx
|-- index.js
```