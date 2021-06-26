# IOS-App-Architecture
## Content
- [Which Architecture Is Right for Me?](https://github.com/egorskikh/IOS-App-Architecture#which-architecture-is-right-for-me)
- [Example App: Koober](https://github.com/egorskikh/IOS-App-Architecture#example-app-koober)
- Objects & Their Dependencies
- Architecture: MVVM
- Architecture: Redux
- Architecture: Elements, Part 1
- Architecture: Elements, Part 2

## Which Architecture Is Right for Me?
### Key points
- Не существует идеальной универсальной архитектуры приложения.
- Вы можете использовать архитектуру для повышения скорости работы вашей команды, повышения качества кода и повышения гибкости кода.
- Выбор «правильного» архитектурного шаблона не гарантирует, что ваша кодовая база будет хорошо спроектирована. Какой узор вы выберете, менее важно, чем то, как вы применяете его на практике.
- Не стесняйтесь смешивать и сочетать разные архитектурные шаблоны.
- Архитектура - это больше искусство, чем наука. Экспериментируйте, учитесь и проявляйте творческий подход.
<br> </br>
## Example App: Koober
### Key points
- [example](https://github.com/egorskikh/IOS-App-Architecture/tree/main/example-app/KooberApp)
- Koober - приложение для вызова кенгуру, является примером приложения, используемым в этой книге.
- Koober включает в себя многие сложности, встречающиеся в реальных приложениях, такие как аутентификация и навигация.
- Полная повторная реализация Koober сопровождает каждую главу об архитектуре.
- Проект Koober Xcode состоит из четырех целей: Koober, Koober_iOS, KooberUIKit и KooberKit.
- MainViewController, LaunchViewController и OnboardingViewController координируют свои действия для запуска Koober.
<br> </br>