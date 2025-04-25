function boostFollowers() {
  const username = document.getElementById("username").value;
  const count = parseInt(document.getElementById("followerCount").value);
  if (!username || isNaN(count)) {
    alert("Please enter valid data");
    return;
  }
  const random = Math.floor(Math.random() * 500) + 100;
  const newCount = random + count;
  document.getElementById("result").innerHTML = `
    <p>@${username}</p>
    <p>Before: ${random}</p>
    <p>After: ${newCount}</p>
    <p>Followers boosted successfully! 🔥</p>
  `;
}
