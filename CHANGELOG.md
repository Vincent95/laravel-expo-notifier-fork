# Changelog

All notable changes to `laravel-expo-notifier` will be documented in this file.

Updates should follow the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## 0.0.7 - 2023-05-29

### What's Changed

- Laravel 10 support by @JamesHemery in https://github.com/YieldStudio/laravel-expo-notifier/pull/16

**Full Changelog**: https://github.com/YieldStudio/laravel-expo-notifier/compare/0.0.6...0.0.7

## 0.0.6 - 2022-12-21

### What's Changed

- fix: dto id type by @JamesHemery in https://github.com/YieldStudio/laravel-expo-notifier/pull/15

**Full Changelog**: https://github.com/YieldStudio/laravel-expo-notifier/compare/0.0.5...0.0.6

## 0.0.5 - 2022-12-21

### What's Changed

- chore: #2 replace cs fixer by pint by @JamesHemery in https://github.com/YieldStudio/laravel-expo-notifier/pull/13
- fix: #11 unique token owner by @JamesHemery in https://github.com/YieldStudio/laravel-expo-notifier/pull/12

**Full Changelog**: https://github.com/YieldStudio/laravel-expo-notifier/compare/0.0.4...0.0.5

## 0.0.4 - 2022-12-13

### What's Changed

- Delete behavior that batch notifications by default
- Delete UrgentExpoNotificationInterface
- Add shouldBatch method on ExpoMessage
- Refactor internal sending
- Add InvalidExpoToken event and DeleteInvalidExpoToken listener (optionnal)

**Full Changelog**: https://github.com/YieldStudio/laravel-expo-notifier/compare/0.0.3...0.0.4

## 0.0.3 - 2022-12-12

### What's Changed

- Add subtitle to ExpoMessage
- Add mutableContent to ExpoMessage
- Fix ExpoMessage serialization
- Channel no longer send notifications if `to` is empty
- Fix notify method of service to serialize messages as Expo message object

**Full Changelog**: https://github.com/YieldStudio/laravel-expo-notifier/compare/0.0.2...0.0.3

## 0.0.2 - 2022-11-23

### What's Changed

- Add possibility to delete one value by @dtangdev in https://github.com/YieldStudio/laravel-expo-notifier/pull/5

**Full Changelog**: https://github.com/YieldStudio/laravel-expo-notifier/compare/0.0.1...0.0.2

## 0.0.1 - 2022-11-18

### What's Changed

- First release 🎉
- Automatically batch non-urgent notifications
- Check push receipts to clear bad tokens

### New Contributors

- @dtangdev made their first contribution in https://github.com/YieldStudio/laravel-expo-notifier/pull/1

**Full Changelog**: https://github.com/YieldStudio/laravel-expo-notifier/commits/0.0.1
