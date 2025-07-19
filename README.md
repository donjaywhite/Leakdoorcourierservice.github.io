function trackPackage() {
  const input = document.querySelector("input").value;
  const result = document.getElementById("tracking-result");

  if (input.trim() === "") {
    result.textContent = "Please enter a tracking number.";
  } else {
    // Simulated tracking response
    result.textContent = `Tracking info for ${input}: In Transit – Expected delivery in 2 days.`;
  }
}
