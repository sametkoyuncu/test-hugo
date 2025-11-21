---
date: '2025-11-21T18:39:56Z'
draft: false
summary: merhaba televole
tags:
- ilk
- yazi
- test
title: ilk-yazi-testi
---

Git çağrısını xcrun’den kurtardım ve sandbox’ta çalışabilir bir ikili aramaya geçtim: HugoWriter/Services/GitService.swift artık Homebrew/CLT/Xcode içindeki gerçek git ikililerini (ve opsiyonel HUGOWRITER\_GIT\_PATH override’ını) sırayla dener ve bulunduğunda doğrudan o yolu kullanıp komutları çalıştırıyor. Bu, /usr/bin/git shim’inin sandbox’ta xcrun hatasına düşmesini engellemeli.
Doğrulamak için: uygulamada GitHub’a bağlan akışını tekrar çalıştırın. Eğer sistemde Homebrew veya CommandLineTools git yoksa kurmanız ya da HUGOWRITER\_GIT\_PATH=/opt/homebrew/bin/git gibi uygun bir yolu set etmeniz gerekiyor.