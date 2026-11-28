---
title: Internationalization and localization
description: "Building software that works across languages, regions and time zones, and adapting it to each market: text encoding, translatable messages, local formats, personal names and time."
why: "Choices about text encoding, message strings and stored times spread through the code and its data from the first release. Retrofitting them for a new market is much harder than designing for it from the start."
reviewed: 2026-11-28
sidebar:
  order: 8
tags: [i18n, l10n, unicode, utf-8, cldr, messageformat, plurals, time-zones, names]
related: [architecture/web-frontend, data/databases]
sources:
  - title: "The Absolute Minimum Every Software Developer Must Know About Unicode in 2023 (Still No Excuses!)"
    author: Nikita Prokopov
    url: "https://tonsky.me/blog/unicode/"
    type: article
    year: 2023
    note: "A post that updates Joel Spolsky's 2003 article on Unicode for a time when almost all text is UTF-8. It explains code points, UTF-8 and UTF-16, grapheme clusters, normalization and locale-dependent operations, and the bugs that come from getting each one wrong."
  - title: "Unicode CLDR Project"
    author: Unicode Consortium
    url: "https://cldr.unicode.org/"
    type: docs
    year: 2026
    note: "The home of CLDR, Unicode Common Locale Data & Rules: formats for dates, numbers, currencies and units, plural rules and sort orders for over 100 languages. Operating systems, browsers and libraries such as ICU build their locale formatting on it, so most applications use it through those APIs. CLDR 49 was released on 22 October 2026."
  - title: "Unicode MessageFormat (UTS #35, Part 9)"
    author: Eemeli Aro, Addison Phillips and the Unicode CLDR committee
    url: "https://www.unicode.org/reports/tr35/tr35-messageFormat.html"
    type: spec
    year: 2026
    note: "The Unicode standard for user interface messages that insert data such as numbers and dates, or change with plurals and grammatical gender. It succeeds ICU MessageFormat and defines the syntax, formatting, selection and error handling for programming languages and APIs to adopt. The current edition is part of CLDR 49."
  - title: "Working with Time and Timezones"
    author: W3C Internationalization Working Group
    url: "https://www.w3.org/TR/timezone/"
    type: guide
    year: 2026
    note: "W3C guidelines and best practices for dates, times and time zones in applications and data formats, edited by Addison Phillips. It defines incremental, field-based and floating time, explains time zone identifiers and summer time, and recommends what to store for timestamps and for past, future and recurring events. The 20 November 2026 version is a Group Note Draft."
  - title: "Personal names around the world"
    author: Richard Ishida
    url: "https://www.w3.org/International/questions/qa-personal-names"
    type: article
    year: 2016
    note: "A W3C Internationalization article, first published in 2011, on how personal names differ between cultures: the order of their parts, patronymics, several family names and non-Latin scripts. It sets out what follows for web forms and databases: one name field or several, field length, native and Latin forms, sorting and forms of address."
---
