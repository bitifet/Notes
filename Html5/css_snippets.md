
Miscellaneous ssl snippets
==========================


Adaptative form layout
----------------------

```
  form {
    display: flex;
    flex-wrap: wrap;

    & > input {
      flex: 1 1 10ch;
      margin: .5rem;

      &[type="email"] {
        flex: 3 1 30ch;
      }
    }
  }
```
