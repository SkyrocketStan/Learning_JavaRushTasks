# 3. Что будет, если переопределить equals, но не переопределить hashCode?

Если таково решение разработчика, то он знает что делает.

Но в целом для некоторых коллекций это будет важно, так как они проверяют сначала 
хеш, и только если он одинаков, то начинают проверять дальше по equals

И в общем два объекта у которых все поля равны будут все равно иметь два разных 
кода.