# teleport-transactions-data
[![npm version](https://badge.fury.io/js/teleport-transactions-data.svg)](https://badge.fury.io/js/teleport-transactions-data)

<table>
  <td>
    <img src="https://raw.githubusercontent.com/Ledoux/teleport-transactions-data/master/icon.png" alt="icon" title="made by @cecilesnips"/>
  </td>
  <td>
    <img src="https://raw.githubusercontent.com/Ledoux/teleport-transactions-data/master/teleport-transactions-data.png" alt="icon" title="made by @cecilesnips"/>
  </td>
  <td>
    A <a href="https://github.com/snipsco/teleport"> Teleport </a> template that helps to create mock and backup mongo data
  </td>
</table>

## How to use it
Simply add it to the list of templates. For instance:
```
tpt -c --templates teleport-express-webrouter,teleport-webpack-react,teleport-react-router,teleport-transactions-backend,teleport-transactions-data,teleport-heroku
```

:warning: Important note, this is a frontend template, it cannot be deployed alone. You should deploy it on side of a backend template (for instance the [teleport express webrouter](https://github.com/snipsco/teleport-express-webrouter)).
