# Создаем свой VPN-сервер
## Загружаем скрипт

```bash
wget https://git.io/Evgenz-mr/MTProxy/vpnsetup.sh -O vpnsetup.sh && sudo sh vpnsetup.sh
```

## После выполнения скрипта:

- Имя: Любое имя для VPN какое вы решите
- Тип: IPsec Xauth PSK (или `IPsec`)
- Адрес сервера: тут `IP-адрес вашего облачного сервера`
- Идентификатор IPSec: оставляете пустым
- Общий ключ IPSec: указываете пароль `IPsec PSK из терминала`
- Имя пользователя: `Username из терминала` (как правило, `vpnuser`)
- Пароль: `Password из терминала`