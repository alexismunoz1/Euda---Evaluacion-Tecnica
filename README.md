# Euda Evaluacion-Tecnica

### 1.POO:

A- ¿Qué es la programación orientada a objetos?

#### Conceptos básicos

- La Programación Orientada a Objetos es un paradigma basado en el concepto de envolver bloques de información y su comportamiento relacionado, en partes especiales llamadas OBJETOS.
- Estos OBJETOS se construyen a partir de un grupo de “planos” definidos por un programador, que se denominan CLASES.

#### Objetos & Clases

![Captura desde 2022-06-24 15-47-41](https://user-images.githubusercontent.com/77214476/175646744-26ccc071-5cda-44e3-93b6-86311e2348a3.png)

- Digamos que tienes un gato llamado Óscar. Óscar es un objeto, una instancia de la clase `Cat`. Cada gato tiene varios atributos estándar: nombre, sexo, edad, peso, color, etc.
Estos son los `campos` de la clase.
- Además, todos los gatos se comportan de forma similar: respiran, comen, corren, duermen, etc. Estos son los `métodos` de la clase.
- Podemos referirnos a los campos y los métodos como los miembros de su clase.

![Captura desde 2022-06-24 15-51-50](https://user-images.githubusercontent.com/77214476/175647318-e982283f-9ea0-43db-83de-79deb33f2d47.png)

- Luna, la gata, también es una instancia de la clase `Cat`. Tiene el mismo grupo de atributos que Óscar. La diferencia está en los valores de estos atributos.
- Por lo tanto, una `clase` es como un plano que define la estructura de los objetos, que son instancias concretas de esa clase.

#### Jerarquías de clase

- Todo va muy bien mientras hablamos de una sola clase. Normalmente, un programa contiene más de una clase. 
Algunas de esas clases pueden estar organizadas en `jerarquías de clase`.
- Digamos que tu vecino tiene un perro llamado Fido. Resulta que los perros y gatos tienen mucho en común: nombre, sexo, edad y color, son `atributos` tanto de perros como de gatos.
- Los perros pueden respirar, dormir y correr igual que los gatos, por lo que podemos la clase base `Animal` que enumenará los atributos y comportamientos que tienen en comun.

![Captura desde 2022-06-24 16-32-04](https://user-images.githubusercontent.com/77214476/175655339-77cd971b-2cae-4e9e-b17a-50a83eea425b.png)

- Una clase padre, se denomina `superclase`. Sus hijas son las `subclases`.
- Las subclases heredan el estado y el comportamiento de su padre y se limitan a definir atributos o comportamientos que son diferentes. Por lo tanto, la clase `Gato` contentrá el método `maullar` y, la clase `Perro` el método `ladrar`.
- Asumiendo que tenemos una tarea relacionada, podemos ir más lejos y extraer una clase más genérica para todos los `Organismos` vivos, que se convertirá en una superclase para `Animal` y `Planta`. *Tal pirámide de clases es una jerarquía*.
- En esta clase jerarquía, la clase `Gato` lo hereda todo de las clases `Animal` y `Organismos`.

![Captura desde 2022-06-24 16-26-27](https://user-images.githubusercontent.com/77214476/175654142-1aaab80f-0360-4713-86b9-d82ff97d35e7.png)


