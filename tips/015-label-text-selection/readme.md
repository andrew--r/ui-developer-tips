# Выделение текста при кликах по `label`

По умолчанию при частых кликах по `label` выделяется текст лейбла. Это стандартное поведение, к которому привыкли пользователи; не отключайте его. Если же вас под угрозой увольнения заставляют отключить выделение текста, запретите выделение только при клике по лейблу, так у пользователя останется возможность выделить его текст:

```css
/* полностью запрещает выделение текста на элементе */
label {
  user-select: none;
}

/* запрещает выделение текста только при кликах по элементу */
label:active {
  user-select: none;
}
```