# expander

Working demo: https://ftd-lang.github.io/expander/

To use in your FPM package, add it to your `FPM.ftd` file as a dependency:

```ftd
-- fpm.dependency: ftd-lang.github.io/expander
```

In any file where you want to use the expander write the following:

```ftd
-- import: ftd-lang.github.io/expander

-- expander.box: box heading

box body

can be multiline.
```
