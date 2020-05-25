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

### Comandos adicionais
```sh
net_graphproportionalfont 0
```

### Mapas de treino de mira

```sh
training_aim_csgo2
```

### Treino de movimentacao

```sh
Jumps Training
```
