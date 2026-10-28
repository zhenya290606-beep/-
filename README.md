flowchart TD
    Admin[Администратор]
    Reg[Регистратор]
    Nurse[Медсестра]
    Doc[Врач]
    Patient[Пациент]

    Admin -->|управляет| Reg
    Admin -->|управляет| Doc
    Admin -->|управляет| Nurse
    Admin -->|управляет| Patient

    Nurse -->|помогает| Doc

    Reg -->|записывает| Patient
    Doc -->|лечит| Patient
    Nurse -->|обслуживает| Patient
```
