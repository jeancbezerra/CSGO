# CSGO

## Launch Options

### 4 Cores / 60 hz

```sh
-novid -tickrate 128 -refresh 60 -high -threads 4 -fullscreen -language english -nojoy -nod3d9ex1 +cl_forcepreload 1

-novid -tickrate 128 -refresh 60 -high -threads 4 -fullscreen -language english -nojoy
```

### 8 Cores / 60 hz

```sh
-novid -tickrate 128 -refresh 60 -high -threads 8 -fullscreen -language english -nojoy -nod3d9ex1 +cl_forcepreload 1

-novid -tickrate 128 -refresh 60 -high -threads 8 -fullscreen -language english -nojoy
```

### 8 Cores / 240 hz

```sh
-novid -tickrate 128 -refresh 240 -high -threads 8 -fullscreen -language english -nojoy -nod3d9ex1 +cl_forcepreload 1

-novid -tickrate 128 -refresh 240 -high -threads 8 -fullscreen -language english -nojoy

-novid -tickrate 128 -refresh 240 -high -threads 8 -fullscreen -language english -nojoy -nod3d9ex1 +cl_forcepreload 1 +rate 198000 +mat_queue_mode -2
```

### 16 cores / 240 hz

```sh
-novid -threads 16 -high -tickrate 128 -refresh 240 +mat_queue_mode -2 +fps_max 300 +r_dynamic 0 +cl_forcepreload 1
```
### Atual Jean

```sh
-novid -tickrate 128 -high -threads 16 +fps_max 0 +cl_showfps 1 +cl_interp 0 +cl_interp_ratio 1 +rate 128000 +cl_updaterate 128 +cl_cmdrate 128 +mat_queue_mode 2 -freq 240 -refresh 240 +cl_forcepreload 1 -nod3d9ex -nojoy
```


### Comandos adicionais
```sh
net_graphproportionalfont 0
```

### Mapas de treino de mira

```sh
training_aim_csgo2
Aim Course 2
```

### Treino de movimentacao

```sh
Jumps Training
```
