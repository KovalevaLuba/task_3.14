## Введение
git - это система контроля версий (VCS, англ. Version Control System ) с открытым исходеным кодом, которая облегчает работу над проектами, позволяя фиксировать все внесенные изменения и храня проект на всех его этапах.

Для хранения проекта (программного кода) используется репозиторий. Т.к. git - это **распределенная**, а не централизованная VCS, то главного репозитория не существует.

Каждый раз, когда мы сохраняем проект, git запоминает, как выглядит проект в этот момент времени, и сохраняет ссылку на него (commit), однако если какие-то файлы не были изменены, то для эффективности git не запоминает эти файлы снова, а просто подтягивает ссылки на их предыдущие версии (из предыдущих коммитов). Таким образом git хранит набор коммитов (которые соеденены ссылками), по которому можно отследить всю историю проекта.

Давайте приступим к работе с git и разберемся на практике, что к чему :)
___
[К оглавлению](readme.md) | [>](beginning.md)