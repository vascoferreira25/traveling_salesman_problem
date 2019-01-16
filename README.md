# Traveling Salesman Problem
## The problem

> "Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city and returns to the origin city?"
> [Wikipedia](https://en.wikipedia.org/wiki/Travelling_salesman_problem)


## How to change population, generations and cities

**Change population:**
```java
// Initialize population
Population pop = new Population(5000, true);

// ...
```

**Change number of generations:**
```java
// Evolve population for 100 generations
pop = GA.evolvePopulation(pop);
for (int i = 0; i < 1000; i++) {
    pop = GA.evolvePopulation(pop);
    System.out.println("Generations: " + i);
}
```

**Add a new city:**
```java
City city21 = new City(360, 120);
TourManager.addCity(city21);
```

## How to run
1. Open project with your favourite IDE (Eclipse, NetBeans, etc.);
2. Open file `Java_Traveling_Salesman_Problem.java`;
3. If you want you can add more cities to the travelling path;
4. Change population and generations;
5. Run the file and check the results.