# Feature File Type Atomic Design

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
|   |   |-- ThemeContext.js
|-- hooks/
|   |-- useWindowSize/
|   |   |-- useWindowSize.js
|-- features/
|   |-- Home/
|   |   |-- contexts/
|   |   |-- hooks/
|   |   |-- pages/
|   |   |   |-- UserProfile.jsx
|   |   |-- utils/
|   |   |-- services/
|   |   |-- store/
|   |   |   |-- userStore.js
|   |   |   |-- store.js
|-- utils/
|   |-- some-common-util/
|   |   |-- someCommonUtil.js/
|-- services/
|   |-- some-common-service/
|   |   |-- someCommonService.js
|-- store/
|   |-- someComonStore.js
|-- App.jsx
|-- index.js
```