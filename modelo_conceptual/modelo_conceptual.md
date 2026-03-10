# Modelos de sistemas

## Casos de uso

### Modelo conceptual

## ¿Qué es un modelo conceptual?

Es una `representación abstracta` de un `problema concreto` abstraída del código. Una forma de representar un sistema de manera abstracta.

## ¿Qué elementos componen un modelo conceptual?

Los elementos son:

1. Entidades 
2. Relaciones/Asociaciones
3. Agente
4. Evento

### Entidades

Estas suelen ser `representadas` como objetos en el código, pero en el `modelo conceptual` todo es `abstracto` por lo que nos referimos a ellas como los `elementos indispensables de un sistema`, estos elementos suelen estar `relacionados/asociados` con otros elementos.

### Agente

Un agente es un `objeto autónomo` que `controla atributos` de otras entidades y asociaciones

### Evento

Un evento es un `objeto  instantaneo`, cualquier `instancia de evento` existen en un sólo estado del sistema.

### Relaciones/Asociaciones

Para que existan asociaciones/relaciones deben haber al menos dos entindades, la relación establece un vínculo entre dos o más entidades.

#### Existen varios tipos de asociaciones/relaciones

### Asociación Binaria

Une `dos entidades` bajo una relación.

### Asociación binaria y multiplicidad

Existen `instancias` para la `relación` entre dos `entidades`, uno a uno, uno a muchos, muchos a uno y muchos a muchos.

### Asociación ternaria

Une `tres entiendades` en una relación, también `puede tener multiplicidad` entre las `entidades` generando multiples `instancias` para cada `relación` entre `entidades`.

### Asociaciones para estructurar

#### Herencia simple

Una entidad `hija` comparte y hereda atributos de una entidad `padre`.

#### Herencia multiple

Varias `entidades hijas` comparten y heredan atributos de una `entidad padre`.

#### Múltiple especialización/generalización

La `especialización` divide a un tipo general en `tipos más específicos` por medio cosas en común.

La `generalización` basado en cosas que comparten los tipos específicos `construye un tipo general`.

### Agregación

Es una `relación débil` porque si se saca `Equipo` el `Jugador` persiste.

###  Composición

`Opuesto` a la `agregación`, las `partes` no pueden existir sin el todo. Si el `TODO` desaparece las `PARTES` también

## Más sobre diagramas de clase

### Atributos derivados

Un `atributo derivado` es un `atributo definido` en terminos de otros `atributos`.

### Asociaciones derivadas

Una `asociación derivada` es una `asociación definida` en términos de otras `asociaciones` en las que participa el `objeto conceptual`

