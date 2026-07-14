<%*
const yesterday = tp.date.now("YYYY-MM-DD", -1);
const tomorrow = tp.date.now("YYYY-MM-DD", 1);

const yesterdayFile = tp.file.find_tfile(yesterday);
const tomorrowFile = tp.file.find_tfile(tomorrow);

const yesterdayLink = yesterdayFile ? `[[${yesterday}|← Yesterday]]` : "← Yesterday (no note yet)";
const tomorrowLink = tomorrowFile ? `[[${tomorrow}|Tomorrow →]]` : "Tomorrow → (no note yet)";

tR += yesterdayLink + " · " + tomorrowLink;
-%>


## 🌱Quick capture
- [ ]

## 📖 Journal


## 📚 Reading notes
-

## ✅ To-do
- [ ]

## 🔗 Permanent notes created today
-