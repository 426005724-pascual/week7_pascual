void main() {
  // Step 4: Basic variables
  String travelerName = "Reden Rugz";
  int travelerAge = 21;
  double distanceWalkedKm = 12.5;
  
  // Step 5: Arithmetic & Extra Credit Operators
  int walkingDays = 3;
  walkingDays++; // Extra Credit: increment operator (3 becomes 4)
  
  double averagePerDay = distanceWalkedKm / walkingDays; // Basic division
  int fullKilometers = distanceWalkedKm ~/ walkingDays;  // Extra Credit: integer division
  double remainingMeters = (distanceWalkedKm % 1) * 1000; // Extra Credit: modulo operator
  
  // Step 5: Comparison producing a boolean
  bool isLongDistanceWalk = distanceWalkedKm >= 10.0;

  // Step 6: Display output using string interpolation in complete sentences
  print("Traveler $travelerName is $travelerAge years old.");
  print("Over $walkingDays days, $travelerName walked a total of $distanceWalkedKm km.");
  print("Average distance per day: ${averagePerDay.toStringAsFixed(2)} km.");
  print("Did $travelerName complete a long-distance walk? $isLongDistanceWalk.");
}