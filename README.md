Определите, принадлежит ли точка с координатами (x, y) заштрихованной области, ограниченной прямой и окружностью.
Границы области:
y = -x
x² + y² = 2.

**1.АЛГОРИТМ**
1. Начало
2. Ввод x,y
3. Проверка условий:
   
   ((x * x + y * y <= 2.0) && (x >= 0.0) && (y <= -x) && ((x * x + y * y == 2.0) || (x == 0.0) || (y == -x)))?
   
   **ДА:** Точка находится на грани области
   
   **НЕТ:** ((x * x + y * y < 2.0) && (x > 0.0) && (y < -x))?
   
   **ДА:** Точка принадлежит области
   
   **НЕТ:** Точка не принадлежит области
   
5. Конец

**БЛОК СХЕМА**

https://viewer.diagrams.net/?tags=%7B%7D&lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%B1%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.drawio&dark=auto#R%3Cmxfile%3E%3Cdiagram%20name%3D%22%D0%A1%D1%82%D1%80%D0%B0%D0%BD%D0%B8%D1%86%D0%B0-1%22%20id%3D%22ClHPE9lSmwtNpOseeqvs%22%3E5Vttb6M4EP41kdqTWmHz%2FjEvbe90u6uVutLefTq5wSVcCc4BaZP79WdjE2xDEpJCcmlXKwePzWDPjGfmGejAHM9XDylazL6SAMcDaASrgTkZQAgc36Q%2FjLIWFGDZnBKmUSBoFeEx%2BhcLoiGoyyjAmTIxJyTOo4VKnJIkwdNcoaE0JW%2FqtGcSq09doBDXCI9TFNepP6Mgn3GqB92K%2FiuOwln5ZLplPjJH5WSxk2yGAvImkcy7gTlOCcn51Xw1xjGTXikXft%2F9ltHNwlKc5G1umIcP9399%2BZF8%2F5a%2BwsnL7y%2BTbz9uGrgIUpavSxlQPlTctDN6m0U5flygKRt5oyqntFk%2Bj2kP0Eu6xQX%2BLcmoygSF83pF8VLwEgSc5nglPU8s%2BQGTOc7TNZ0yk6TqCRG%2BVRoArqAJLqYh%2BuuyL2xA6D%2FccK5ERC%2BElA6QGGwjMbq5XBVNk%2BSyPCUveExiklJiQhIm4ucojjUSiqMwod0pfSKm9BETX0RtdCgG5lEQsEePUrJMAsyWbzBWJMnFiQJuozLoNH%2FC2pExoMv03PKatqOivTtKYWZdYY6mL9tW9FV2O9eXcEA4qJ3znSafBEPmPZjUY5Rl0VRVpyroRivfLSFbiCPFMcqjV3VtktjsHXYsnvCdRHQjlWQ961aVLQAak4ws0ykW98kuYz8rR2OVozTEeY1VoarN1o%2FXnnuA9opN7eBl1bVM2T6KLknzGQlJguK7iqrpuZrzhZCFMIW%2FcZ6vxTFDy5yohoJXUf4Hu50Kkvf%2BlEYmK8G56Kwlc6pbT6OlHGYWluN7rm8Dz3Chqeh142JPpFerzSEswgm9pLNQHOOYhCmaU%2FkscBrRBTBXqI59rwYOD1XP0QqXCUh3octpCF2%2BrbhC6Ln7Tlln3tD%2BaNGraEdQxCrWWoVk4XjdVeTyVHWZFtTV5fYVvErH3Yn%2F887p%2F4Dk%2FSpfeEL%2F57hqgmjrQbFnj%2Be1OXnpjMyfltn5Mm1o1O3fdDR%2FZegHoBY9ujsAoMMD4H%2FyBMBTD4B%2F2gPgX07oaThLTszW9ZTSqzAvpnDKIsXKDpx%2FlgzQF9Hr5hnNo5jKbDhg2NxBc7Z4MWGMsikKIkSHvpKE6MPFI4yCS1aYFuPhL%2FijjSnfJ6Ol4dMVZU51YpQ%2F13x9JSex4qsrGhWNX3h0pFNHhSlwylpeYMyfTzdDDzplJg3xttY1rlbyrLBiYGwY1OW3h%2BW2Nd2s2i1p33YpM2WP7pj9b1or310539DmXync6Oqur0sW9JwU9lFu%2BRiHDFokkL4a2qDbmztuVf34oHn7RhWCi%2B3oeXstp%2BhO8ObleE85cXe2Je7DTcq%2BKTsNRfEJ8vqTXJeylfyetV5Bh0ULivZev1F0zWLUkCpbE8FBTOBsgVT0MiS2sJzcDZgApmpEjlEzItgbmmiFuv9%2FRmRvRX%2BFLZTer%2FMape2pftXcVYx7n2YuCJdvTY6YyrbnQlUWA5zFqjFDqcrRvi18RBVIOfd3RNIWNWnPOpU777KuSZ3sBeEaaHCcsWtD3kkAkKe%2FI%2BoZAMEuseyZlX7uag4ANA2X%2FmnlbFfPgHtWbamNU1Z3zog%2Fa45bLCZboKRxNRJejZlHvglQ%2BnLVCF2LXzZSvBJkHfniuhNs%2Bz5gK6PawzEsh4hSYONCUwXZAXAEDQjGdM1bVy%2FmGbeOenhqhaHuwl6rIuhHhY8OvLV8Vfi2cwsdNShZvQn%2FIxTgWueY7o4csy32tMvuvQQhPRWcbgDpSNzCWkeBqIfBzF4TXqihT6i9FPF6%2Bwyj%2FArqEqyvVQFDByonQSS1vKY7%2FVxmZW9P3tGtVziLG1DTg34qmdA4lZVZB0Cgxq%2BxxNG%2BjE%2BxgCZYYOiQs%2B2XWDqnk2NX%2B7MpTs%2BKj9ed4%2B2zgr6V53wq5e2X97Gas09cVoCHlAk%2Fxser2qtM3zhSdTojAHROfeuuFdbt9tP6AzGSv6sOP5SylRIOsQzF6RKiNHzYX8tN9iqyu%2BzkghCyjFG8rRil3%2FdjwKpFSeeI8gXtVn8Fw49f9cdE5t1%2F%3C%2Fdiagram%3E%3C%2Fmxfile%3E

**2. РЕАЛИЗАЦИЯ ПРОГРАММЫ**

**3. РЕЗУЛЬТАТ ПРОГРАММЫ**

(зависит от введенных значений)

**4. ФАМИЛИЯ, ГРУППА**
Битюкова Юлия, БОТИ-261
