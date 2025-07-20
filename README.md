# HumanEmotions
Emotions that can be articulated for everyone.

  <section class="intro">
    <p>Welcome to a space that embraces every feeling — loud or quiet, fleeting or forever. Whether you're looking for the right word to express how you feel or simply seeking to understand, you're in the right place.</p>
  </section>

  <section class="emotions-grid">
    <div class="emotion-card joy">
      <h2>Joy</h2>
      <p>Light-hearted, ecstatic, hopeful, playful, satisfied.</p>
      <ul>
        <li><strong>Elation</strong>: A rush of intense happiness.</li>
        <li><strong>Gratitude</strong>: Warmth from appreciation.</li>
        <li><strong>Serenity</strong>: Calm, peaceful contentment.</li>
      </ul>
    </div>

    <div class="emotion-card sadness">
      <h2>Sadness</h2>
      <p>Heavy-hearted, gloomy, wistful, vulnerable, tired.</p>
      <ul>
        <li><strong>Melancholy</strong>: A gentle sadness with no clear cause.</li>
        <li><strong>Grief</strong>: The ache of loss and

/* Reset and Base */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  background-color: #f7f7f7;
  color: #333;
  padding: 20px;
}

/* Header */
header {
  text-align: center;
  padding: 40px 20px;
  background-color: #e0f7fa;
  border-radius: 12px;
  margin-bottom: 30px;
}

header h1 {
  font-size: 2.5rem;
  color: #00796b;
}

header p {
  font-size: 1.1rem;
  color: #555;
  margin-top: 10px;
}

/* Intro Section */
.intro {
  max-width: 700px;
  margin: 0 auto 30px;
  text-align: center;
  font-size: 1.1rem;
  color: #666;
}

/* Emotions Grid */
.emotions-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 20px;
  margin-bottom: 50px;
}

/* Emotion Cards */
.emotion-card {
  background: #ffffff;
  padding: 20px;
  border-left: 5px solid #ccc;
  border-radius: 10px;
  transition: transform 0.2s ease;
}

.emotion-card:hover {
  transform: translateY(-4px);
}

.emotion-card h2 {
  margin-bottom: 10px;
  font-size: 1.5rem;
}

/* Thematic Colors */
.joy { border-color: #fdd835; }
.sadness { border-color: #90a4ae; }
.anger { border-color: #ef5350; }
.love { border-color: #f48fb1; }
.fear { border-color: #9575cd; }

ul {
  margin-top: 10px;
  padding-left: 20px;
}

ul li {
  margin-bottom: 6px;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  color: #999;
  font-size: 0.9rem;
}
