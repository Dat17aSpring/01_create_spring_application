# MoviesController 
placed in the src -> main -> java -> "the rest of the pacages"    

````java    

  package dk.kea.clbo.studentsapp.controllers;
  import org.springframework.stereotype.Controller;
  import org.springframework.web.bind.annotation.GetMapping;

  /**
   * Created by clbo on 24/11/2017.
   */
  @Controller
  public class MoviesController {

      @GetMapping("/")
      public String index(){
          return "movies";
      }
  }

````      
# index.html
placed in the src -> resources -> templates folder

````html

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <title>Movies</title>
    </head>
    <body>
      <h1>Movies</h1>
      <p>When Harry meet Sally</p>
      <p>Avatar</p>
      <p>Blade Runner 2017</p>
    </body>
    </html>

````    

