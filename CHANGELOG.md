# Yii Test Support Change Log

## 3.0.1 under development

- no changes in this release.

## 3.0.0 June 29, 2022

- Chg #45: Update `psr/simple-cache` version to `^2.0|^3.0` (@vjik)

## 2.0.0 June 16, 2022

- Chg #43: Raise the minimum `psr/log` version to `^2.0|^3.0` and the minimum PHP version to 8.0 (@rustamwin)

## 1.4.0 March 24, 2022

- Enh #40: Add custom callback for method `has()` of `SimpleContainer` (@vjik)
- Bug #40: Catch only `NotFoundException` instead of `Throwable` in `SimpleContainer::has()` method (@vjik)

## 1.3.0 March 15, 2021

- Enh #29: Add `SimpleLogger` class, which is an implementation of `LoggerInterface` (@devanych)

## 1.2.1 March 07, 2021

- Enh #26: Support PSR Container v2.0 (@roxblnfk)

## 1.2.0 February 23, 2021

- Enh #24: Add `SimpleEventDispatcher::getEventClasses()` that return classes of dispatched events (@vjik)

## 1.1.0 February 22, 2021

- Enh #23: Add `SimpleEventDispatcher::clearEvents()` that clear all events in event dispatcher (@vjik)

## 1.0.0 December 24, 2020

- Initial release.
