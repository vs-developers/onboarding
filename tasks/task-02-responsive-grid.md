# 📦 Task 02: Responsive Grid Layout

🎯 **Мета:** Навчитись створювати адаптивну сітку для карток або елементів за допомогою Bootstrap Grid System.

---

## 📋 Що потрібно зробити:

1. Створи нову сторінку `pages/grid.tsx`
2. Додай заголовок `"Список карток"`
3. Створи блок з картками (мінімум 6 карток), кожна має містити:
   - заголовок (`<h5>`)
   - зображення (`<img>`)
   - короткий текст або кнопку

4. Використовуй Bootstrap grid:
   - по **3 картки в ряд** на десктопі
   - по **2** на планшеті
   - по **1** на мобільному

---

## 📦 Приклад структури (JSX):
```tsx
<div className="container">
  <div className="row">
    <div className="col-12 col-sm-6 col-lg-4">
      <div className="card">
        <img src="/images/sample.jpg" className="card-img-top" alt="..." />
        <div className="card-body">
          <h5 className="card-title">Картка 1</h5>
          <p className="card-text">Опис картки</p>
        </div>
      </div>
    </div>
    {/* інші картки */}
  </div>
</div>