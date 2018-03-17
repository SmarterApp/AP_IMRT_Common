# IMRT Common
A collection of common classes leveraged between the IMRT projects.

## Entity Classes
The common entity classes that are shared across projects are included in `model` and are annotated with the `@Entity` annotation.  If you want to include them in a springboot application ensure that you have `@EntityScan({"org.opentestsystem.ap.imrt.common"})` added to a Configuration or SpringApplication class.

