Atom React and Styled Components Snippets
====================================================================================================================================================================

An [Atom](https://atom.io/) snippet library for react and styled components. This library uses ES6 syntax and does not include semicolons.

Install
-------

Go to `Packages > Settings View > Open` once in settings go to the Install tab and search for **react-and-styled-component-snippets**

Restart Atom

Development
-----------

```sh
$ cd ~/.atom/packages
$ git clone https://github.com/thommymo/react-and-styled-components-atom-snippets
$ cd atom-react-snippets
$ apm install
$ apm link
```

Snippets
--------

General ES6 Snippets

| Trigger       | Content |
| -------:      | ------- |
| `im`          | import empty |
| `ex`          | export empty |
| `exd`         | export default empty |
| `sf`          | stateless function |


React Snippets

| Trigger       | Content |
| -------:      | ------- |
| `ri`          | import react |
| `ric`         | import react with Component |
| `ripc`        | import react with PureComponent |
| `rip`         | import react with PropTypes |
| `ricp`        | import react with Component and PropTypes |

React Lifecycle Snippets

| Trigger       | Content |
| -------:      | ------- |
| `rcdm`        | componentDidMount method |
| `rcwm`        | componentWillMount method |
| `rcwr`        | componentWillReceiveProps method |
| `rscu`        | shouldComponentUpdate method |
| `rcwup`       | componentWillUpdate method |
| `rcdup`       | componentDidUpdate method |
| `rcwun`       | componentWillUnmount method |
| `rcdc`        | componentDidCatch method |

React Skeletons

| Trigger       | Content |
| -------:      | ------- |
| `rcs`         | class skeleton |
| `rsc`         | stateless component |
| `rscp`        | stateless component with PropTypes |
| `rscpr`       | stateless component with return |

React Utilities Snippets

| Trigger       | Content |
| -------:      | ------- |
| `rss`         | setState({ ... }) |
| `rtp`         | this.props. |
| `rts`         | this.state. |

Styled Components Snippets

| Trigger       | Content |
| -------:      | ------- |
| `sci`         | Styled Components: import |
| `scir`        | Styled Components: import with React |
| `scp`         | Styled Components: Props |
| `scs`         | Styled Components: styled |

Contributing
------------

1.	Fork it!
2.	Create your feature branch: `git checkout -b my-new-feature`
3.	Commit your changes: `git commit -m 'Add some feature'`
4.	Push to the branch: `git push origin my-new-feature`
5.	Submit a pull request

License
-------

MIT License

Credit
------

These snippets are heavily based on work by [webbushka](https://github.com/webbushka/)
