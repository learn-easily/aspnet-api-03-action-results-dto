# ASP.NET Core Web API — ლექცია 3 — API-ის პასუხი: IActionResult და DTO

ანიმაციური HTML პრეზენტაცია + ლექტორის სცენარი.

| ფაილი | რა არის |
|---|---|
| `index.html` | პრეზენტაცია (40 სლაიდი) |
| `script.html` | ლექციის სცენარი — წასაკითხად / დასაბეჭდად |
| `deck/` | წყარო: სლაიდები და შენიშვნები (`ar.html`), ძრავი (`engine.*`), ბილდი (`build_deck.py`) |

## გამოყენება

1. გახსენი `index.html` Chrome-ში ან Edge-ში, გადაიტანე პროექტორზე, დააჭირე `F`.
2. დააჭირე `Ctrl+Shift+P` — გაიხსნება **ლექტორის ფანჯარა** სცენარით.
3. ნავიგაცია **მხოლოდ ისრებით**: `→` შემდეგი, `←` წინა (`Shift+→` — შემდეგი სლაიდი).

სხვა კლავიშები: `N` შენიშვნები · `O` ყველა სლაიდი · `A` სლაიდის ყველა ნაბიჯი.

## ცვლილების შეტანა

```bash
cd deck && pip install pygments && python3 build_deck.py ar
cp ../out/lecture-03-action-results-dto.html ../index.html && cp ../out/lecture-03-action-results-dto-script.html ../script.html
```
