# TitanFit
My personal training business website
import React from "react";

export default function PersonalTrainingWebsite() {
  return (
    <div className="min-h-screen bg-gradient-to-b from-black via-zinc-900 to-black text-red-600 font-sans">
      <header className="bg-gradient-to-r from-red-800 to-red-600 text-white p-10 shadow-2xl border-b-4 border-red-900">
        <div className="max-w-6xl mx-auto">
          <h1 className="text-5xl font-extrabold tracking-wide mb-2">Hamed's Personal Training</h1>
          <p className="text-xl text-red-200 italic">Empowering your fitness journey, one session at a time.</p>
        </div>
      </header>

      <nav className="bg-red-900 text-white py-4 sticky top-0 z-50 shadow-md">
        <div className="max-w-6xl mx-auto flex justify-around text-sm md:text-base">
          <a href="#about" className="hover:text-yellow-300">About</a>
          <a href="#services" className="hover:text-yellow-300">Services</a>
          <a href="#benefits" className="hover:text-yellow-300">Why Train With Me</a>
          <a href="#packages" className="hover:text-yellow-300">Packages</a>
          <a href="#testimonials" className="hover:text-yellow-300">Testimonials</a>
          <a href="#contact" className="hover:text-yellow-300">Contact</a>
        </div>
      </nav>

      <main className="max-w-6xl mx-auto px-6 py-12 space-y-20">
        <section id="about">
          <h2 className="text-4xl font-bold text-white mb-4 border-b border-red-700 pb-2">🔥 About Me</h2>
          <p className="text-lg leading-relaxed text-red-300">
            I'm Hamed, a certified personal trainer in Western Sydney with a passion for helping clients achieve real, long-lasting transformations. My coaching style is focused, personalized, and results-driven. Whether your goal is weight loss, muscle gain, or improved mobility, I’ll guide you every step of the way.
          </p>
        </section>

        <section id="services">
          <h2 className="text-4xl font-bold text-white mb-4 border-b border-red-700 pb-2">💪 Services</h2>
          <ul className="grid grid-cols-1 md:grid-cols-2 gap-4 text-lg text-red-300 list-disc list-inside">
            <li>One-on-One Personal Training</li>
            <li>Tailored Bodybuilding Programs</li>
            <li>Rehabilitation & Injury-Conscious Workouts</li>
            <li>Custom Nutrition & Supplement Plans</li>
            <li>Strength & Conditioning</li>
            <li>Functional Movement & Mobility Training</li>
            <li>Online Coaching & Check-ins</li>
            <li>Postural Correction & Flexibility</li>
          </ul>
        </section>

        <section id="benefits">
          <h2 className="text-4xl font-bold text-white mb-4 border-b border-red-700 pb-2">🚀 Why Train With Me?</h2>
          <ul className="list-disc list-inside text-lg text-red-300 space-y-2">
            <li>Customized Programs for All Fitness Levels</li>
            <li>Flexible Scheduling to Fit Your Life</li>
            <li>Motivational & Supportive Environment</li>
            <li>Advanced Tracking Tools to Measure Progress</li>
            <li>Beginner-Friendly and Expert Coaching</li>
          </ul>
        </section>

        <section id="packages">
          <h2 className="text-4xl font-bold text-white mb-4 border-b border-red-700 pb-2">📦 Training Packages</h2>
          <div className="grid md:grid-cols-3 gap-8 text-red-300">
            <div className="bg-red-950 p-6 rounded-xl shadow-lg">
              <h3 className="text-xl font-bold text-white mb-2">Starter</h3>
              <ul className="list-disc list-inside">
                <li>3 sessions/week</li>
                <li>Basic diet & training plan</li>
                <li>Email support</li>
                <li>$300/month</li>
              </ul>
            </div>
            <div className="bg-red-950 p-6 rounded-xl shadow-lg border border-red-600">
              <h3 className="text-xl font-bold text-white mb-2">Pro</h3>
              <ul className="list-disc list-inside">
                <li>5 sessions/week</li>
                <li>Full diet plan + supplements</li>
                <li>Weekly progress checks</li>
                <li>$500/month</li>
              </ul>
            </div>
            <div className="bg-red-950 p-6 rounded-xl shadow-lg">
              <h3 className="text-xl font-bold text-white mb-2">Elite</h3>
              <ul className="list-disc list-inside">
                <li>Daily training access</li>
                <li>Meal planning service</li>
                <li>24/7 messaging support</li>
                <li>$800/month</li>
              </ul>
            </div>
          </div>
        </section>

        <section id="testimonials">
          <h2 className="text-4xl font-bold text-white mb-4 border-b border-red-700 pb-2">💬 Testimonials</h2>
          <div className="grid gap-6">
            <blockquote className="bg-zinc-800 text-red-300 p-4 rounded shadow-md italic">
              "Training with Hamed changed my life. I lost 10kg and gained confidence I never had before." – Sarah M.
            </blockquote>
            <blockquote className="bg-zinc-800 text-red-300 p-4 rounded shadow-md italic">
              "Highly professional, friendly, and results-focused. Best investment I’ve made in my health." – David R.
            </blockquote>
          </div>
        </section>

        <section id="contact">
          <h2 className="text-4xl font-bold text-white mb-4 border-b border-red-700 pb-2">📞 Contact</h2>
          <p className="text-lg text-red-300">Email: <a href="mailto:hamed@fitcoach.com" className="underline hover:text-white">hamed@fitcoach.com</a></p>
          <p className="text-lg text-red-300">Instagram: <a href="https://instagram.com/hamedfit" className="underline hover:text-white">@hamedfit</a></p>
        </section>
      </main>

      <footer className="bg-gradient-to-r from-red-900 to-red-800 text-center py-6 text-sm text-red-200 border-t border-red-700">
        &copy; {new Date().getFullYear()} Hamed's Personal Training. All rights reserved.
      </footer>
    </div>
  );
}
