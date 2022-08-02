# TỐI ƯU MÁY CHỦ
Tối ưu hóa dành cho những người mới và những server tầm trung
Nên dùng cho: Survival, Skyblock
Minigame không nên sử dụng vì giảm trải nghiệm đáng kể, pvp có thể lỗi hit

Thêm 1.19.1 configs mới nhất.

## Tham khảo từ
Mình tham khảo optimize từ:
* [YouHaveTrouble's Guide](https://github.com/YouHaveTrouble/minecraft-optimization)
* [Server Optimization Guide](https://www.spigotmc.org/threads/guide-server-optimization%E2%9A%A1.283181/)
* [Paper Chan’s Little Guide](https://eternity.community/index.php/paper-optimization/)
* [Anarchy Server Optimization](https://github.com/moom0o/AnarchyExploitFixes/wiki/Anarchy-Server-Optimization-Guide)
* [Top 10 Things You Missed Optimizing](https://blog.airplane.gg/10-things-you-missed-optimizing-survival-mc/) 
* [Shockbyte Reducing Lag](https://shockbyte.com/billing/knowledgebase/21/Reducing-Lag)
* [Purpur Documentation](https://purpur.pl3x.net/docs/Configuration/)

## Khuyến nghị

### Hạn chế sử dụng plugins
* **Stacker plugins** - việc stack các mob trồng lên nhau thì máy chủ sẽ phải tiếp tục tái sinh ra những con quái mới. Async thì không sao nếu sync như 1.16+ thì rất lag có thể tràn ram
* **Item removal plugins** - Khá là vô dụng vì việc xóa rác đã có spigot.yml giúp
* **Plugin managers** - Hạn chế việc load/unload plugins bằng Plugman vì nó sẽ thành chạy ngầm và tràn ram (ram tăng theo từng người chơi).

### Kiếm tra timings
Việc này rất quan trong khi kiểm tra nguyên nhân lag

Hãy sử dụng [BirdFlop's Optimize](https://www.birdflop.com/) @Discord bot on their [Discord guild](https://discord.com/invite/nmgtX5z) that you cand send the timings report to, it will tell you a few good ways to optimise your server.

### Khuyên dùng
* [Insights](https://www.spigotmc.org/resources/insights-super-configurable-region-limits-asynchronous-scans-1-17-x.56489/) - Cho phép bạn đặt giới hạn lưu trữ, redstone, mục cho các khu vực, phần hoặc đảo trên các máy chủ skyblock / oneblock.

* [Aikar Flags](https://blog.airplane.gg/aikar-flags/) - Java startup flags, the best to run a minecraft server.

* [AntiRedstoneClock](https://www.spigotmc.org/resources/antiredstoneclock-worldguard-plotsquard-support-1-8-1-17.18557/) - Tắt bộ lặp redstone khi TPS máy chủ của bạn giảm.

* [Spark](https://www.spigotmc.org/resources/antiredstoneclock-worldguard-plotsquard-support-1-8-1-17.18557/) - Allows you to analyse your servers CPU and memory usage.

* [Chunky](https://github.com/pop4959/Chunky) - Pre-generates chunks for better performance on survival servers.

<br>
