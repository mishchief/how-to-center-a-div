# how-to-center-a-div

Regular CSS:

```
.center-div {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  min-height: 100vh;
}

 <div class="center-div">
 Ayoo I'm in the center of your screen ya fool
 </div>
```

Inline Styles:

```
<div style={{
    display: "flex",
    justifyContent: "center",
    alignItems: "center",
    textAlign: "center",
    minHeight: "100vh",
    }}>
    I'm in the center again but this time with inline styles. Dummy.
</div>
```

Material UI:

```
<Container sx={{
    display: "flex",
    justifyContent: "center",
    alignItems: "center",
    textAlign: "center",
    minHeight: "100vh",
    }}>
    Pretty much the same thing as inline styles but using the sx prop.
</Container>
```
