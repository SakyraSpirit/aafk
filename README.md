name: 网页挂机

on:
  schedule:
    - cron: '*/30 * * * *'  # 每30分钟运行一次

jobs:
  keep_alive:
    runs-on: ubuntu-latest
    steps:
      - name: 访问网页
        run: curl [https://example.com](https://replit.com/@zhixian04052008/Slobos-Aternos-AFK-Bot)
