<!-- Сгенерировано из src/legal.ts: правь там, а не здесь. -->

# Политика конфиденциальности MedKoalu

Версия от 30.10.2026. Контакт: beks0928.studio@gmail.com

## Коротко

MedKoalu хранит твои лекарства и отметки приёма на твоём телефоне. На наш сервер они попадают, только если ты вступил в общую семью. Часть других данных (ник, серия дней, почта, итоги месяца) уходит на сервер, когда ты сам включаешь соответствующую функцию: всё перечислено ниже. Мы не показываем рекламу, не продаём данные и не отслеживаем тебя.

## Что хранится на телефоне

Названия лекарств, дозировки, расписание и курсы, остаток таблеток, отметки приёма и их время, имя, время подъёма и отбоя, язык, запомненные штрих-коды. Эти данные остаются на телефоне, пока ты не вступил в общую семью (см. ниже). Если в iPhone включена резервная копия iCloud, данные приложения могут попасть и в неё. Если удалить приложение, данные на телефоне стираются вместе с ним (копия в iCloud остаётся, пока ты не удалишь её сам). Чтобы стереть данные ещё и на сервере, нажми «Удалить аккаунт и все данные» в настройках до удаления приложения.

## Что уходит с телефона

1. Аккаунт и вход. Когда нужна функция с сервером (друзья, семья, почта, отчёт), приложение создаёт для тебя анонимный аккаунт: без телефона и пароля. Если ты входишь через Apple или Google, мы получаем твою почту (у Apple это может быть скрытый адрес) и идентификатор аккаунта. Для входа через Apple мы дополнительно храним токен, нужный, чтобы при удалении аккаунта отозвать доступ приложения в твоём Apple ID.

2. Друзья (только если ты создал профиль и дал согласие). На наш сервер отправляются: ник, длина серии, число дней, отметка «сегодня всё выпито» и твой код друга; их видят твои друзья. Названия лекарств, дозы, время приёма и остаток не отправляются никогда.

3. Поиск по штрих-коду. Номер штрих-кода вместе с твоим IP-адресом отправляется в открытые базы Open Food Facts и UPCitemdb, чтобы найти название: по номеру эти сервисы могут узнать, какой товар ты сканируешь. Фото упаковки отправляется, только если название не нашлось на телефоне и ты дал согласие (см. раздел «Камера»).

4. Почта (только если ты её указал, этот шаг можно пропустить). Почта сохраняется на нашем сервере, чтобы подтвердить её по ссылке из письма. Если ты отметил галочку «Присылать ежемесячный отчёт», мы раз в месяц присылаем письмо с итогами: сколько доз по расписанию и сколько отмечено, число идеальных дней и серия. Для этого эти числа хранятся на нашем сервере до удаления аккаунта. Названия лекарств в письма и на сервер для отчёта не попадают. Письма отправляет почтовый сервис (Google Gmail или сервис рассылок). Отключить отчёт можно переключателем в настройках или ссылкой «Отписаться» в письме. Телефон мы не просим никогда.

5. Общая семья (только если ты создал семью или вступил по приглашению и дал отдельное согласие). Лекарства (названия, дозировки, расписание, курсы, остаток) и отметки приёма хранятся на нашем сервере и видны всем участникам твоей семьи, включая детей. По умолчанию участники могут менять и отмечать твои лекарства: это можно запретить для каждого человека или для всех сразу в настройках семьи. Если ты удаляешь лекарство, его данные и отметки сразу стираются с сервера. Если ты выходишь из семьи или тебя убирают, все твои лекарства стираются с сервера. У тех, кто не в семье, лекарства остаются только на телефоне.

6. Покупки. Платёжные данные мы не видим. RevenueCat получает идентификатор твоего аккаунта и сведения о покупке, чтобы открыть платные функции.

7. Уведомления-напоминания создаются на самом телефоне.

## Камера

Камера используется для сканирования штрих-кода и чтения названия на упаковке. Сначала изображение читается на самом телефоне и после чтения удаляется. Если название не нашлось на телефоне, после твоего согласия (его спрашивают один раз) фото отправляется на наш сервер и в Google (модель Gemini), чтобы прочитать название, дозу и количество. Мы и Google не сохраняем фото. Название лекарства попадает в общий список, который помогает распознавать упаковки без интернета; в этом списке нет ничего о тебе. Не снимай аптечную наклейку с твоим именем.

## Твои права

Ты можешь в любой момент: выгрузить свои данные (Настройки, «Экспортировать данные»; в выгрузку входят данные с телефона, данные на сервере можно запросить письмом на контактный адрес); удалить профиль друзей (вкладка «Друзья»); удалить все данные на телефоне и на сервере, включая почту, итоги отчёта и данные семьи, а для входа через Apple ещё и отозвать доступ приложения (Настройки, «Удалить аккаунт и все данные»); отключить ежемесячный отчёт (переключатель в настройках или ссылка в письме). Сведения о покупках хранят RevenueCat и магазин приложений: чтобы их удалили, напиши на контактный адрес. После удаления аккаунта данные на нашем сервере стираются.

## Кто обрабатывает данные

Данные профиля друзей, почту, итоги для отчёта и данные общей семьи хранит сервис Supabase. Вход через Apple и Google выполняют Apple и Google. Письма отправляет почтовый сервис (Google Gmail или сервис рассылок). Фото упаковки, если название не нашлось на телефоне и ты согласился, читает Google (модель Gemini). Покупки обрабатывает RevenueCat вместе с App Store и Google Play. Поиск по штрих-коду выполняют Open Food Facts и UPCitemdb. Мы не передаём данные другим лицам и не используем их для рекламы.

## Дети

Приложение не предназначено для детей младше 13 лет, и мы сознательно не собираем их данные. Роль «ребёнок» в общей семье для тех, кому исполнилось 13 лет. Для младших используй профили близких: они остаются только на телефоне родителя. Детям до 18 лет лекарства должен вносить родитель или опекун.

## Изменения

Если политика изменится, новая версия появится в приложении с новой датой.

---

# Privacy Policy for MedKoalu

Version of 30.10.2026. Contact: beks0928.studio@gmail.com

## In short

MedKoalu keeps your medications and intake marks on your phone. They reach our server only if you join a shared family. Some other data (nickname, streak, email, monthly totals) goes to the server when you turn on the matching feature yourself: everything is listed below. We show no ads, sell no data and do not track you.

## Kept on the phone

Medication names, doses, schedules and courses, pill counts, intake marks and their times, your name, wake and bed times, language, remembered barcodes. This stays on the phone until you join a shared family (see below). If iCloud Backup is on for the iPhone, the app data can be part of it. Deleting the app erases the data on the phone with it (the iCloud copy stays until you delete it yourself). To erase the data on the server too, tap "Delete account and all data" in Settings before deleting the app.

## What leaves the phone

1. Account and sign-in. When a feature needs the server (friends, family, email, report) the app creates an anonymous account for you: no phone number or password. If you sign in with Apple or Google we receive your email (Apple may give a hidden address) and an account ID. For Apple sign-in we also keep a token that lets us revoke the app's access in your Apple ID when you delete the account.

2. Friends (only if you create a profile and consent). Sent to our server: nickname, streak length, day count, a "done today" flag and your friend code; your friends see them. Medication names, doses, times and pill counts are never sent.

3. Barcode lookup. The barcode number is sent with your IP address to the open databases Open Food Facts and UPCitemdb to find a name: from the number these services can tell which product you scan. A pack photo is sent only when the name is not found on the phone and you have agreed (see Camera).

4. Email (only if you give one, this step can be skipped). The email is stored on our server to confirm it with a link in a message. If you tick "Send a monthly report", once a month we send a message with totals: doses scheduled and marked, perfect days and streak. For this the numbers are kept on our server until you delete the account. Medication names never reach the messages or the server for the report. Messages are sent by a mail service (Google Gmail or a mailing service). You can turn the report off with the switch in Settings or the "Unsubscribe" link in the message. We never ask for a phone number.

5. Shared family (only if you create a family or join by invitation and give separate consent). Medications (names, doses, schedules, courses, pill counts) and intake marks are stored on our server and visible to everyone in your family, including children. By default members can change and mark your medications: you can forbid this for each person or for everyone in the family settings. When you delete a medication, its data and marks are erased from the server at once. If you leave the family or are removed, all your medications are erased from the server. For people who are not in a family, medications stay on the phone only.

6. Purchases. We never see payment details. RevenueCat receives your account ID and purchase details to unlock paid features.

7. Reminder notifications are created on the phone itself.

## Camera

The camera is used to scan barcodes and to read the name on a pack. The image is first read on the phone itself and deleted after reading. If no name is found on the phone, after your consent (asked once) the photo is sent to our server and to Google (the Gemini model) to read the name, strength and count. Neither we nor Google keep the photo. The medication name joins a shared list that helps recognize packs without internet; the list contains nothing about you. Keep a pharmacy sticker with your name out of the shot.

## Your rights

At any time you can: export your data (Settings, "Export data"; the export holds the data on the phone, server data can be requested by email to the contact address); delete your friends profile (Friends tab); delete all data on the phone and on the server, including email, report totals and family data, and for Apple sign-in also revoke the app's access (Settings, "Delete account and all data"); turn off the monthly report (switch in Settings or the link in the message). Purchase records are kept by RevenueCat and the app store: to have them deleted, write to the contact address. After the account is deleted, the data on our server is erased.

## Who processes data

Friends profile data, your email, report totals and shared family data are stored by Supabase. Apple and Google run sign-in with Apple and Google. Messages are sent by a mail service (Google Gmail or a mailing service). A pack photo, when the name is not found on the phone and you agreed, is read by Google (the Gemini model). Purchases are handled by RevenueCat together with the App Store and Google Play. Barcode lookups are done by Open Food Facts and UPCitemdb. We do not pass data to anyone else and do not use it for ads.

## Children

The app is not intended for children under 13 and we knowingly collect no data from them. The "child" role in a shared family is for people aged 13 or older. For younger children use relatives profiles: they stay on the parent's phone only. For anyone under 18, a parent or guardian should enter the medications.

## Changes

If this policy changes, the new version will appear in the app with a new date.
