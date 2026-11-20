# kobudo-register

A register of Japanese swordsmen and martial schools (*koryū*) of the late Edo,
Meiji and early Shōwa periods: one Markdown file per person or school, with
structured front matter and a prose record.

It is the reference data behind the [Inner Dharma](https://innerdharma.org)
writing project by Mark Raugas. The essays and books that use these records are
at <https://innerdharma.org>; start there if you want to read rather than search.

## What is here

| Folder | Contents |
|---|---|
| `kenshi/` | People: swordsmen, spearmen, jūjutsu teachers and officials of the Kōbusho and the institutions that followed it. |
| `ryuha/` | Schools. |
| `myoseki/` | Hereditary succession names. |
| `references.md` | The sources cited by the records. |

Each file is named for its key (`kenshi/kubota-sugane.md`). It has two parts: a
YAML front-matter block between `---` lines, described under [Schema](#schema),
and the written record in Markdown, with footnotes to the sources.

The repository holds text only. Images that accompany some records on the site
are not included.

## Reading the records

- Links between records are ordinary relative links, so they can be followed
  here on GitHub or in any Markdown viewer.
- Citations in the text link into [references.md](references.md), which lists
  every source the records cite, by key. The same keys appear under `refs:` in
  the front matter. The project's full source register is at
  <https://innerdharma.org/refs/>.
- In the front matter, `xref:` values name another record in the form
  `/kenshi/<key>.html`; read that as the file `kenshi/<key>.md`.
- Readings of names are given only where a source supports them.

These are close readings of historical sources, not academic histories, and
they are revised as the sources are checked. Corrections are welcome.

## Index

### People (57)

| Name | 漢字 | Dates | School |
|---|---|---|---|
| [Amano Hachirō](kenshi/amano-hachiro.md) | 天野八郎 | 1831–1868 | Jikishinkage-ryū |
| [Amano Shōshō](kenshi/amano-shosho.md) | 天野将曹 | 1819–? | Jikishinkage-ryū |
| [Awa Kenzō](kenshi/awa-kenzo.md) | 阿波研造 |  |  |
| [Chiba Shūsaku](kenshi/chiba-shusaku.md) | 千葉周作 |  | Ittō-ryū, Hokushin Ittō-ryū |
| [Chūjō Kinnosuke](kenshi/chuujo-kinnosuke.md) | 中條金之助 | 1827–1896 | Shingyōtō-ryū, Hokushin Ittō-ryū, Totsuka-ha Yōshin-ryū |
| [Fujita Taiichirō](kenshi/fujita-taiichiro.md) | 藤田泰一郎 |  | Shintō Munen-ryū |
| [Fukuda Hachinosuke](kenshi/fukuda-hachinosuke.md) | 福田八之助柳儀斎 | 1828–1879 | Tenjin Shin'yō-ryū |
| [Hakomori Yosaburō](kenshi/hakomori-yosaburo.md) | 箱守与三郎 | 1837–? | Jikishinkage-ryū |
| [Henmi Sōsuke](kenshi/henmi-sosuke.md) | 逸見宗助 | 1843–1894 | Tatsumi-ryū, Kyōshin Meichi-ryū |
| [Hiraiwa Jirōdayū](kenshi/hiraiwa-jirodayu.md) | 平岩次郎太夫 | Ansei 2 (1855) to Keiō 2 (1866) |  |
| [Honme Yarijirō](kenshi/honme-yarijiro.md) | 本目縫次郎 |  | Jikishinkage-ryū |
| [Iba Sōtarō](kenshi/iba-sotaro.md) | 伊庭惣太郎 |  | Shingyōtō-ryū |
| [Ido Kinpei](kenshi/ido-kinpei.md) | 井戸金平 | Ansei–Bunkyū (the Kōbusho years); described as about thirty at the time of the bouts below | Hōzōin-ryū |
| [Imahori](kenshi/imahori.md) | 今堀 |  | Jikishinkage-ryū |
| [Inoue Hachirō](kenshi/inoue-hachiro.md) | 井上八郎 |  | Hokushin Ittō-ryū |
| [Kagawa Zenjirō](kenshi/kagawa-zenjiro.md) | 香川善治郎 | 1849–1921 | Mutō-ryū |
| [Kajikawa Yoshimasa](kenshi/kajikawa-yoshimasa.md) | 梶川義正 |  | Ono-ha Ittō-ryū |
| [Kawaji Toshiyoshi](kenshi/kawaji-toshiyoshi.md) | 川路利良 | 1834–1879 | Jikishinkage-ryū |
| [Kawashima Takashi](kenshi/kawashima.md) | 川島堯 | 1883–1957 | Jikishinkage-ryū, Heki-ryū, Fujishin-ryū, Ittō-ryū |
| [Kobayashi Sadayuki](kenshi/kobayashi-sadayuki.md) | 小林定之 |  | Hokushin Ittō-ryū |
| [Komai Hangorō](kenshi/komai-hangoro.md) | 駒井半五郎 | Ansei–Keiō (Kōbusho service attested from the Ansei roster to at least Bunkyū 3) | Hōzōin-ryū |
| [Kondō Yanosuke](kenshi/kondo-yanosuke.md) | 近藤弥之助 |  | Ittō-ryū |
| [Kubota Sugane](kenshi/kubota-sugane.md) | 窪田清音 | 1791–1867 | Tamiya-ryū |
| [Kunii Zen'ya](kenshi/kunii-zenya.md) | 國井善弥 |  |  |
| [Matsudaira Chikaranosuke](kenshi/matsudaira-chikaranosuke.md) | 松平忠敏 |  | Ryūgō-ryū, Muteki-ryū, Shingyōtō-ryū, Shintō-ryū |
| [Matsuoka Yorozu](kenshi/matsuoka-yorozu.md) | 松岡万 | 1838–1891 | Chūya-ha Ittō-ryū |
| [Matsushita Seiichirō](kenshi/matsushita-seiichiro.md) | 松下誠一郎 |  | Shingyōtō-ryū |
| [Matsuzaki Namishirō](kenshi/matsuzaki-namishiro.md) | 松崎浪四郎 | 1833–1896 | Katōda Shinkage-ryū |
| [Mitsuhashi Kan'ichirō](kenshi/mitsuhashi-kanichiro.md) | 三橋鑑一郎 | 1841–1909 | Musashi-ryū, Tōgun-ryū, Kyōshin Meichi-ryū |
| [Mitsuhashi Torazō](kenshi/mitsuhashi-torazo.md) | 三橋虎蔵 |  | Shingyōtō-ryū |
| [Mochida Moriji](kenshi/mochida-moriji.md) | 持田盛二 | 1885–1974 | Nakanishi Ittō-ryū, Hōshin-ryū |
| [Monna Tadashi](kenshi/monna-tadashi.md) | 門奈正 |  | Hokushin Ittō-ryū |
| [Naitō Takaharu](kenshi/naito-takaharu.md) | 内藤高治 | 1862–1929 | Hokushin Ittō-ryū |
| [Nakayama Hakudō](kenshi/nakayama-hakudo.md) | 中山博道 |  |  |
| [Nakayama Tatsusaburō](kenshi/nakayama-tatsuburo.md) | 中山辰三郎 |  | Ittō-ryū, Jikishinkage-ryū, Yōshin-ryū |
| [Namiki Yasushi](kenshi/namiki.md) | 並木靖 | 1926–1999 | Jikishinkage-ryū, Heki-ryū |
| [Odani Seiichirō](kenshi/odani-seiichiro.md) | 男谷精一郎 | 1798–1864 | Jikishinkage-ryū, Hōzōin-ryū |
| [Okumura Sakonta](kenshi/okumura-sakonta.md) | 奥村左近太 | 1842–1903 | Jikishinkage-ryū, Okumura Nitō-ryū |
| [Ōnishi Hidetaka](kenshi/onishi.md) | 大西英隆 | 1906–1966 | Jikishinkage-ryū |
| [Saimura Gorō](kenshi/saimura-goro.md) | 斎村五郎 | 1887–1969 | Abetate-ryū, Hokushin Ittō-ryū |
| [Sakakibara Kenkichi](kenshi/sakakibara-kenkichi.md) | 榊原鍵吉 | 1830–1894 | Jikishinkage-ryū |
| [Shibata Emori](kenshi/shibata-emori.md) | 柴田衛守 | 1849–1925 | Kurama-ryū, Chūya-ha Ittō-ryū |
| [Shida Utanosuke](kenshi/shida-utanosuke.md) | 信太歌之助 | 1837–? | Jikishinkage-ryū, Kitō-ryū |
| [Shimada Toranosuke](kenshi/shimada-toranosuke.md) | 島田虎之助 | 1814–1852 | Jikishinkage-ryū, Ittō-ryū, Kitō-ryū |
| [Shimoe Hidetarō](kenshi/shimoe-hidetaro.md) | 下江秀太郎 |  | Hokushin Ittō-ryū |
| [Shingai Tadaatsu](kenshi/shingai-tadaatsu.md) | 真貝忠篤 | 1842–1920 | Tamiya-ryū |
| [Takahashi Deishū](kenshi/deishu.md) | 高橋泥舟 | 1835–1903 | Jitokuin-ryū, Ninshin-ryū |
| [Takahashi Hatsuji](kenshi/takahashi-hatsuji.md) | 高橋初次 | 1838–? | Araki-ryū |
| [Takano Sasaburō](kenshi/takano-sasaburo.md) | 高野佐三郎 | 1862–1950 | Nakanishi-ha Ittō-ryū |
| [Takayama Minesaburō](kenshi/takayama-minesaburo.md) | 高山峰三郎 | 1835–1899 | Jikishinkage-ryū |
| [Toda Hachirōzaemon](kenshi/toda-hachirozaemon.md) | 戸田八郎左衛門 |  | Tamiya-ryū |
| [Tokunō Sekishirō](kenshi/tokuno-sekishiro.md) | 得能関四郎 | 1842–1908 | Jikishinkage-ryū |
| [Ueda Umanosuke](kenshi/ueda-umanosuke.md) | 上田馬之助 | 1831–1890 | Kyōshin Meichi-ryū |
| [Umezaki Yaichirō](kenshi/umezaki-yaichiro.md) | 梅崎弥一郎 | 1847–1913 | Katōda Shinkage-ryū, Tsuda Ichiden-ryū |
| [Yamada Jirōkichi](kenshi/yamada-jirokichi.md) | 山田次朗吉 | 1863–1930 | Jikishinkage-ryū |
| [Yamaoka Tesshū](kenshi/yamaoka-tesshu.md) | 山岡鉄舟 | 1836–1888 | Jitokuin-ryū, Ninshin-ryū, Mutō-ryū |
| [Yoshida Katsunosuke](kenshi/yoshida-katsunosuke.md) | 吉田勝之助 | Ansei–Keiō (Kōbusho service from the Ansei roster to at least Bunkyū 3) | Hōzōin-ryū |

### Schools (22)

| Name | 漢字 |
|---|---|
| [Chūya-ha Ittō-ryū](ryuha/chuya-itto-ryu.md) | 忠也派一刀流 |
| [Hokushin Ittō-ryū](ryuha/hokushin-ryu.md) | 北辰一刀流 |
| [Hōzōin-ryū](ryuha/hozoin-ryu.md) | 宝蔵院流 |
| [Ittō-ryū](ryuha/itto.md) | 一刀流 |
| [Jikishinkage-ryū](ryuha/jikishinkage-ryu.md) | 直心影流 |
| [Jitokuin-ryū](ryuha/jitokuin-ryu.md) | 自得院流 |
| [Kashima Shin-ryū](ryuha/kashima-shinryu.md) | 鹿島神流 |
| [Katōda Shinkage-ryū](ryuha/katoda-shinkage-ryu.md) | 加藤田神陰流 |
| [Kitō-ryū](ryuha/kito-ryu.md) | 起倒流 |
| [Kyōshin Meichi-ryū](ryuha/kyoshin-meichi-ryu.md) | 鏡新明智流 |
| [Musashi-ryū](ryuha/musashi-ryu.md) | 武藏流 |
| [Ōshima-ryū](ryuha/oshima-ryu.md) | 大島流 |
| [Ryūgō-ryū](ryuha/ryugo-ryu.md) | 柳剛流 |
| [Seigō-ryū](ryuha/seigo-ryu.md) | 制剛流 |
| [Shingyōtō-ryū](ryuha/shingyoto-ryu.md) | 心形刀流 |
| [Shintō Munen-ryū](ryuha/shinto-munen-ryu.md) | 神道無念流 |
| [Taisha-ryū](ryuha/taisha-ryu.md) | たい捨流 |
| [Tamiya-ryū](ryuha/tamiya-ryu.md) | 田宮流 |
| [Tatsumi-ryū](ryuha/tatsumi-ryu.md) | 立身流 |
| [Tenjin Shin'yō-ryū](ryuha/tenjin-shinyo.md) | 天神真楊流 |
| [Totsuka-ha Yōshin-ryū](ryuha/totsuka-ryu.md) | 戸塚派楊心流 |
| [Tsuda Ichiden-ryū](ryuha/tsuda-ichiden-ryu.md) | 津田一伝流 |

### Succession names (1)

| Name | 漢字 |
|---|---|
| [Momonoi Shunzō](myoseki/momoi-shunzo.md) | 桃井春蔵 |

## Schema

Front matter is YAML. Three fields are required in `kenshi/` and `ryuha/`
records; everything else is optional and appears only where the sources support
it. Records vary a great deal in depth, and an absent field means "not
recorded here", not "does not exist".

### Fields common to all records

| Field | Type | Meaning |
|---|---|---|
| `key` | string, **required** | The record's identifier. Always equal to the file name without `.md`. |
| `pref_label` | map, **required** | The preferred form of the name. `value` (kanji) and `romaji` are required; `kana` and `readings` (alternative readings) are optional. |
| `title` | string | Display title, normally the same as `pref_label.romaji`. |
| `excerpt` | string | One- or two-sentence summary. |
| `entity_type` | `person` \| `kenshi` \| `ryuha` \| `myoseki` | Kind of record, where stated (`person` and `kenshi` mean the same). The folder is authoritative. |
| `date` | date | When the record was written or last substantially revised. Not a historical date. |
| `refs` | list of strings | Citation keys; each is listed in [references.md](references.md). |
| `tags`, `topic`, `category`, `project`, `projects` | strings / lists | Editorial grouping used by the site. |
| `book_omit` | boolean | The record is left out of the printed books. |

### Assessment fields

These say how firm a record is. They can appear at the top level or on a single
entry inside `names`, `lineage` or `students`.

| Field | Type | Meaning |
|---|---|---|
| `reliability` | string | A prose assessment of the sources and of what remains uncertain. |
| `corroboration` | string | How well attested: `external` (confirmed outside the tradition) or `internal` (the tradition's own account only); inside `lineage` and `students` it may be a short note. |
| `contested` | boolean | Sources disagree on a material point. |
| `single_source` | boolean | The claim rests on one source. |
| `excluded_source_check` | boolean | The record was checked against the project's list of sources it does not rely on. |
| `disambiguation` | string | Distinguishes this person or school from another of the same or a similar name. |

### People (`kenshi/`)

| Field | Type | Meaning |
|---|---|---|
| `names` | list of maps | Every recorded name, one entry each. See below. |
| `dates` | map | `birth` and `death`, each a map with `seireki` (Western year) and where known the era date; `floruit` (free text) where birth and death are unknown; `age_at_death`. |
| `ryuha` | list of strings | Schools the person belonged to, by name. |
| `lineage` | list of maps | One entry per line of study: `school` or `ryuha`, `art`, `teacher`, `generation`, `dojo`, `entered`, `rank`, `branch`, `note`, `source`, `xref` (key of a related record), plus assessment fields. |
| `students` | list of maps | Notable pupils: `name`, `role`, `dates`, `note`, `source`, `xref`, plus assessment fields. |
| `fellow_disciples` | list of maps | Contemporaries under the same teacher: `name`, `note`, `source`, `xref`. |
| `origin` | map | `han` (domain), `kuni` (province), `honkan` (ancestral seat), `residence`, `current_place` (modern location). |
| `mibun` | string | Status or house standing (hatamoto, domain retainer and so on). |
| `kanshoku` | list of strings | Offices and posts held. |
| `eiten` | list of strings | Honours and titles received. |
| `keizu` | map | Family: `father`, `adoptive`, `brother`, `siblings`, `children`, `marriage`. |
| `grave` | map | `bochi` (burial place), `bohi` (gravestone or inscription), `coords`. |
| `works` | list of strings | Writings by the person. |
| `external_ids` | map | Authority identifiers: `ndlna` (National Diet Library), `viaf`, `wikidata`, `cinii`. Empty where no authority record was found. |

Each entry in `names` has a `type` from a fixed vocabulary, a `romaji` reading,
and optionally `value` (kanji), `kana`, `role`, `note` and `source`:

| `type` | Meaning |
|---|---|
| `uji` | Clan name (氏) |
| `kabane` | Hereditary title (姓) |
| `myoji` | Family name (苗字) |
| `yomyo` | Childhood name (幼名) |
| `tsusho` | Common or everyday name (通称) |
| `imina` | Formal personal name (諱) |
| `azana` | Courtesy name (字) |
| `go` | Art name or pen name (号) |
| `henmei` | A changed or later name (変名) |
| `kaimyo` | Posthumous Buddhist name (戒名) |
| `shigo` | Posthumous title (諡号) |
| `yago` | House or shop name (屋号) |
| `myoseki` | A hereditary succession name (名跡) |

`role` marks the two names that make up the preferred form:
`canonical-surname` and `canonical-given`.

### Schools (`ryuha/`)

| Field | Type | Meaning |
|---|---|---|
| `founder` | string | Founder, with kanji and dates where known. |
| `parent` | string | The school or schools it derives from. |
| `period` | string | When it was founded or was active. |
| `art` | list of strings | Disciplines taught (`kenjutsu`, `sojutsu`, `jujutsu` and so on). |
| `name_variance` | string | Variant ways of writing the name. |

### Succession names (`myoseki/`)

A succession name is one name carried by several people in turn.

| Field | Type | Meaning |
|---|---|---|
| `holders` | list of maps, **required** | One entry per holder, with `generation`, `imina` and what is known of each. |
| `myoseki_begins` | integer | The generation from which the name was actually used. |
| `retroactive_numbering` | string | Notes where earlier heads were numbered after the fact. |
| `sequence_contested`, `sequence_note` | boolean, string | The order of holders is disputed, and why. |
| `institution` | map | The dōjō or house attached to the name: `name`, `founded`, `note`. |
| `ryuha` | list of maps | The school the name belongs to, with notes on its name and formation. |

## Status

This repository is a snapshot, updated occasionally. The working copy is kept
elsewhere, so the history here will be short.

## Copyright

Copyright 2026 by Mark Raugas. Content licensed
[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/) unless
otherwise noted.
