#### Пример файла

![code-222x280](https://user-images.githubusercontent.com/11923488/209478830-d0a22279-5cc0-4c7e-ab63-e0a794d88e1e.png)

I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"

*Выделение курсивом*

**Выделение жирным**

***Выделение жирным курсивом***

```elixir
def deps do
  [
    {:finitomata, "~> 0.1"}
  ]
end
```

## Changelog

- `0.9.0` — [FIX] malformed callbacks had the FSM broken
- `0.8.2` — last error is now kept in the state (credits to @egidijusz)


~~Зачеркнутый текст~~

`Hi man`

```sql
SELECT ara FROM chupa 
```

* Первый
* Второй

- Первый
- Второй
- Третий

+ Первый
+ Второй

1. Первый
2. Второй

# Заголовок первого уровня

## Заголовок второго уровня

### Заголовок третьего уровня

#### Заголовок четвертого уровня

##### Заголовок пятого уровня

###### Заголовок шестого уровня

просто текст

> ### Syntax Definition {: .tip}
>
> `Mermaid` **state diagram** format is literally the same as `PlantUML`, so if you want to use it, specify `syntax: Finitomata.PlantUML` and
> if you want to use **mermaid graph**, specify `syntax: Finitomata.Mermaid`. The latter is the default.

Basically, it looks more or less like this

### `PlantUML`
