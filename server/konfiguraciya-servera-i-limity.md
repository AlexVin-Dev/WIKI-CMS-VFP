---
icon: gear
---

# Конфигурация сервера и лимиты

{% hint style="warning" %}
**Раздел будет дополняться.**

Последнее обновление - 11 Мая  2025
{% endhint %}

### Конфигурация выделенного сервера

> **CPU** _(Процессор)_: Common KVM processor 2.40GHz\
> **RAM** _(Оперативная память)_: 16 GB \
> **SSD** _(Накопитель)_: 512 GB\
> **Сеть:** 1000 Мбит/сек \
> **Местоположение:** Россия, Москва&#x20;

### Ядро сервера:

На наших всех серверах стоит ядро [Purpur](https://purpurmc.org/) 1.21.7.

### _spigot.yml_

```yaml
world-settings:
  default:
    mob-spawn-range: 4
    item-despawn-rate: 6000
    arrow-despawn-rate: 1200
    trident-despawn-rate: 1200
    entity-activation-range:
      animals: 32
      monsters: 32
      raiders: 64
      misc: 16
      water: 16
      villagers: 32
      flying-monsters: 32
```
