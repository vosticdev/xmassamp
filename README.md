# xmassamp
 Simple module for xmas made in pawn lang!

#Dependencies
- Ysi includes 5x ( https://github.com/pawn-lang/YSI-Includes ) 
- MySQL R41-4 ( https://github.com/pBlueG/SA-MP-MySQL )

#Add this in your server database
```sql
CREATE TABLE `winter_settings` (
  `username` varchar(24) NOT NULL DEFAULT 'Maryland',
  `map` tinyint(4) NOT NULL DEFAULT 0,
  `breath` tinyint(4) NOT NULL DEFAULT 0,
  `fallsnow` tinyint(4) NOT NULL DEFAULT 0
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;

```


---
Include it in main mode, change handler for query and enjoy.

#Enjoy <3
