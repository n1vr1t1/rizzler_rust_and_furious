# rizzler_rust_and_furious
Rizzler is a struct with 0 fields and 7 methods which are modified versions of the interfaces inside the common crate.
Each method charges a vector of Strings with irresistible pick up lines...


*Sigh ... what am i doing with my life?

Once the Vector is all charged up, the correspondent interface of the common crate is called and only after the execution of the same
a (terrible) random  pick up line is printed on the terminal! the methods return both the standard interface result and a sentence selected according to the result of the same.
Seriously, why did you buy this?

# Functions of the rizzler
## Destroy_with_rizz:
Calls "destroy" interface

### Syntax
``` rust
destroy_with_rizz(robot:  & mut impl Runnable, world: &mut World, direction:Direction)-> (String,Result<usize, LibError>)
```
### Usage
```rust
println!("{}",rizzler::init_error_rizz()(*parameters))
```
## Put_with_rizz:
Calls "put" interface
 
### Syntax
``` rust
put_with_rizz(robot: & mut impl Runnable, world: &mut World, content: Content, quantity:usize, direction: Direction)-> (String,Result<usize, LibError>)
```

### Usage
``` rust
println!("{}",rizzler::put_with_rizz(*parameters))
```

## Discover_tiles_with_rizz:
Calls "discover tile" interface

### Syntax
``` rust
discover_tiles_with_rizz(robot: &mut impl Runnable, world: &mut World, to_discover: &[(usize, usize)])->(String, Result<HashMap<(usize, usize), Option<Tile>>, LibError>)
```

### Usage
``` rust
Rizzler::println!("{}",rizzler::discover_tiles_with_rizz(*parameters))
```

## Discover_tiles_with_rizz:
Calls "discover tile" interface

### Syntax
``` rust
discover_tiles_with_rizz(robot: &mut impl Runnable, world: &mut World, to_discover: &[(usize, usize)])->(String, Result<HashMap<(usize, usize), Option<Tile>>, LibError>)
```

### Usage
``` rust
Rizzler::println!("{}",rizzler::discover_tiles_with_rizz(*parameters))
```

## Teleport_with_rizz:
Calls "teleport" interface
```

### Syntax
``` rust
teleport_with_rizz(robot: &mut impl Runnable, world: &mut World, coordinates: (usize, usize))-> (String, Result<TileMatrix, LibError>)
```

### Usage
``` rust
println!("{}",rizzler::teleport_with_rizz(*parameters))
```

## Look_at_sky_with_rizz:
Calls "look_at_sky" interface
```

### Syntax
``` rust
look_at_sky_with_rizz(world: &World) -> (String, EnvironmentalConditions)
```

### Usage
``` rust
println!("{}",rizzler::look_at_sky_with_rizz(*parameters))
```

## Craft_with_rizz:
Calls "craft" interface

### Syntax
``` rust
craft_with_rizz(robot: &mut impl Runnable, content: Content)-> (String, Result<Content, LibError>)
```

### Usage
``` rust
println!("{}",rizzler::craft_with_rizz(*parameters))
```
