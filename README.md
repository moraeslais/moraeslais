import React from 'react';
import { Github, Linkedin, Twitter, Mail, Globe, Coffee } from 'lucide-react';

export function ReadmePreview() {
  return (
    <div className="w-full bg-[#0d1117] text-white">
      {/* Header Banner */}
      <div className="w-full relative">
        <div className="h-[250px] bg-gradient-to-r from-[#A5586E] via-[#C85C9D] to-[#E284C1] flex items-center justify-center relative overflow-hidden">
          <div className="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxkZWZzPjxwYXR0ZXJuIGlkPSJncmlkIiB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHBhdHRlcm5Vbml0cz0idXNlclNwYWNlT25Vc2UiPjxwYXRoIGQ9Ik0gNDAgMCBMIDAgMCAwIDQwIiBmaWxsPSJub25lIiBzdHJva2U9InJnYmEoMjU1LDI1NSwyNTUsMC4xKSIgc3Ryb2tlLXdpZHRoPSIxIi8+PC9wYXR0ZXJuPjwvZGVmcz48cmVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSJ1cmwoI2dyaWQpIi8+PC9zdmc+')] opacity-30"></div>
          
          <div className="z-10 text-center">
            <h1 className="text-8xl font-bold text-[#FDB8E7] animate-pulse mb-4">YOUR NAME</h1>
            <p className="text-2xl text-white/90">Full Stack Developer | Creative Coder | Tech Enthusiast</p>
          </div>
        </div>
        
        {/* Wave SVG */}
        <svg className="w-full h-[50px] -mt-1" viewBox="0 0 1440 100" fill="none" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
          <path d="M0,50 Q360,0 720,50 T1440,50 L1440,100 L0,100 Z" fill="#0d1117"/>
        </svg>
      </div>

      <div className="max-w-6xl mx-auto px-6 py-12">
        {/* Profile Section */}
        <div className="grid md:grid-cols-2 gap-8 mb-12">
          <div className="flex flex-col items-center justify-center bg-[#161b22] rounded-lg p-8 border border-[#30363d]">
            <div className="w-full max-w-[300px] aspect-square rounded-lg mb-6 flex items-center justify-center overflow-hidden border-4 border-[#FDB8E7] shadow-2xl">
              <img 
                src="https://i.pinimg.com/originals/92/33/80/92338017c079bea4f1250ed4a3056117.gif" 
                alt="Coding animation"
                className="w-full h-full object-cover"
              />
            </div>
            <h3 className="text-2xl font-bold text-[#FDB8E7] mb-4">👋 Welcome to my GitHub Profile!</h3>
            <div className="flex items-center gap-2 text-sm text-[#E284C1]">
              <span>Profile Views:</span>
              <span className="bg-[#C85C9D] text-white px-3 py-1 rounded">1,234</span>
            </div>
          </div>

          <div className="bg-[#161b22] rounded-lg p-8 border border-[#30363d]">
            <h2 className="text-3xl font-bold text-[#FDB8E7] mb-4 flex items-center gap-2">
              🚀 About Me
            </h2>
            <pre className="bg-[#0d1117] p-4 rounded-lg text-sm overflow-x-auto border border-[#30363d]">
              <code className="text-[#E284C1]">
{`const developer = {
  name: "Your Name",
  role: "Full Stack Developer",
  location: "🌍 Earth",
  languages: ["JavaScript", "TypeScript", "Python"],
  technologies: {
    frontend: ["React", "Next.js", "Vue"],
    backend: ["Node.js", "Express", "Django"],
    database: ["MongoDB", "PostgreSQL"],
    tools: ["Docker", "AWS", "Git"]
  },
  currentlyLearning: "AI & Machine Learning",
  hobbies: ["Coding", "Gaming", "Reading"],
  motto: "Code is poetry ✨"
};`}
              </code>
            </pre>
          </div>
        </div>

        {/* Connect Section */}
        <div className="text-center mb-12">
          <h3 className="text-2xl font-bold text-[#FDB8E7] mb-6">🌐 Connect with me</h3>
          <div className="flex flex-wrap justify-center gap-4">
            <a href="#" className="bg-[#E284C1] hover:bg-[#C85C9D] transition-colors px-6 py-3 rounded-lg font-semibold text-white flex items-center gap-2">
              <Linkedin size={20} />
              LinkedIn
            </a>
            <a href="#" className="bg-[#C85C9D] hover:bg-[#A5586E] transition-colors px-6 py-3 rounded-lg font-semibold text-white flex items-center gap-2">
              <Twitter size={20} />
              Twitter
            </a>
            <a href="#" className="bg-[#A5586E] hover:bg-[#8A5568] transition-colors px-6 py-3 rounded-lg font-semibold text-white flex items-center gap-2">
              <Mail size={20} />
              Email
            </a>
            <a href="#" className="bg-[#FDB8E7] hover:bg-[#E284C1] transition-colors px-6 py-3 rounded-lg font-semibold text-[#1a1a1a] flex items-center gap-2">
              <Globe size={20} />
              Portfolio
            </a>
          </div>
        </div>

        {/* Neon Divider */}
        <div className="w-full h-1 bg-gradient-to-r from-[#A5586E] via-[#FDB8E7] to-[#A5586E] rounded-full mb-12 shadow-[0_0_20px_rgba(253,184,231,0.5)]"></div>

        {/* Tech Stack */}
        <div className="mb-12">
          <h2 className="text-3xl font-bold text-[#FDB8E7] mb-8 text-center">💻 Tech Stack & Tools</h2>
          
          <div className="space-y-6">
            <div>
              <h3 className="text-xl font-semibold text-[#E284C1] mb-3">Frontend</h3>
              <div className="flex flex-wrap gap-2">
                {['HTML5', 'CSS3', 'JavaScript', 'TypeScript', 'React', 'Next.js', 'Vue.js', 'Tailwind'].map((tech, idx) => (
                  <span key={idx} className="bg-[#E284C1] text-white px-4 py-2 rounded-lg text-sm font-semibold hover:scale-105 transition-transform cursor-pointer">
                    {tech}
                  </span>
                ))}
              </div>
            </div>

            <div>
              <h3 className="text-xl font-semibold text-[#C85C9D] mb-3">Backend</h3>
              <div className="flex flex-wrap gap-2">
                {['Node.js', 'Express', 'Python', 'Django', 'FastAPI'].map((tech, idx) => (
                  <span key={idx} className="bg-[#C85C9D] text-white px-4 py-2 rounded-lg text-sm font-semibold hover:scale-105 transition-transform cursor-pointer">
                    {tech}
                  </span>
                ))}
              </div>
            </div>

            <div>
              <h3 className="text-xl font-semibold text-[#A5586E] mb-3">Database & Cloud</h3>
              <div className="flex flex-wrap gap-2">
                {['MongoDB', 'PostgreSQL', 'MySQL', 'Redis', 'AWS', 'Docker'].map((tech, idx) => (
                  <span key={idx} className="bg-[#A5586E] text-white px-4 py-2 rounded-lg text-sm font-semibold hover:scale-105 transition-transform cursor-pointer">
                    {tech}
                  </span>
                ))}
              </div>
            </div>

            <div>
              <h3 className="text-xl font-semibold text-[#FDB8E7] mb-3">Tools</h3>
              <div className="flex flex-wrap gap-2">
                {['Git', 'VS Code', 'Figma', 'Postman'].map((tech, idx) => (
                  <span key={idx} className="bg-[#FDB8E7] text-[#1a1a1a] px-4 py-2 rounded-lg text-sm font-semibold hover:scale-105 transition-transform cursor-pointer">
                    {tech}
                  </span>
                ))}
              </div>
            </div>
          </div>
        </div>

        {/* Neon Divider */}
        <div className="w-full h-1 bg-gradient-to-r from-[#A5586E] via-[#FDB8E7] to-[#A5586E] rounded-full mb-12 shadow-[0_0_20px_rgba(253,184,231,0.5)]"></div>

        {/* GitHub Stats */}
        <div className="mb-12">
          <h2 className="text-3xl font-bold text-[#FDB8E7] mb-8 text-center">📊 GitHub Statistics</h2>
          
          <div className="grid md:grid-cols-2 gap-6 mb-6">
            <div className="bg-[#161b22] rounded-lg p-6 border border-[#30363d] hover:border-[#C85C9D] transition-colors">
              <div className="flex items-center justify-between mb-4">
                <h3 className="text-lg font-semibold text-[#FDB8E7]">GitHub Stats</h3>
                <Github className="text-[#C85C9D]" size={24} />
              </div>
              <div className="space-y-3">
                <div className="flex justify-between">
                  <span className="text-[#E284C1]">Total Stars:</span>
                  <span className="text-[#FDB8E7] font-bold">150+</span>
                </div>
                <div className="flex justify-between">
                  <span className="text-[#E284C1]">Total Commits:</span>
                  <span className="text-[#FDB8E7] font-bold">1,200+</span>
                </div>
                <div className="flex justify-between">
                  <span className="text-[#E284C1]">Total PRs:</span>
                  <span className="text-[#FDB8E7] font-bold">50+</span>
                </div>
                <div className="flex justify-between">
                  <span className="text-[#E284C1]">Followers:</span>
                  <span className="text-[#FDB8E7] font-bold">100+</span>
                </div>
              </div>
            </div>

            <div className="bg-[#161b22] rounded-lg p-6 border border-[#30363d] hover:border-[#C85C9D] transition-colors">
              <div className="flex items-center justify-between mb-4">
                <h3 className="text-lg font-semibold text-[#FDB8E7]">Streak Stats</h3>
                <span className="text-2xl">🔥</span>
              </div>
              <div className="space-y-3">
                <div className="flex justify-between">
                  <span className="text-[#E284C1]">Current Streak:</span>
                  <span className="text-[#FDB8E7] font-bold">15 days</span>
                </div>
                <div className="flex justify-between">
                  <span className="text-[#E284C1]">Longest Streak:</span>
                  <span className="text-[#FDB8E7] font-bold">45 days</span>
                </div>
                <div className="flex justify-between">
                  <span className="text-[#E284C1]">Total Contributions:</span>
                  <span className="text-[#FDB8E7] font-bold">2,500+</span>
                </div>
              </div>
            </div>
          </div>

          <div className="grid md:grid-cols-2 gap-6">
            <div className="bg-[#161b22] rounded-lg p-6 border border-[#30363d] hover:border-[#C85C9D] transition-colors">
              <h3 className="text-lg font-semibold text-[#FDB8E7] mb-4">Top Languages</h3>
              <div className="space-y-3">
                <div>
                  <div className="flex justify-between mb-1">
                    <span className="text-[#E284C1]">JavaScript</span>
                    <span className="text-[#FDB8E7]">45%</span>
                  </div>
                  <div className="w-full bg-[#0d1117] rounded-full h-2">
                    <div className="bg-[#E284C1] h-2 rounded-full" style={{width: '45%'}}></div>
                  </div>
                </div>
                <div>
                  <div className="flex justify-between mb-1">
                    <span className="text-[#E284C1]">TypeScript</span>
                    <span className="text-[#FDB8E7]">30%</span>
                  </div>
                  <div className="w-full bg-[#0d1117] rounded-full h-2">
                    <div className="bg-[#C85C9D] h-2 rounded-full" style={{width: '30%'}}></div>
                  </div>
                </div>
                <div>
                  <div className="flex justify-between mb-1">
                    <span className="text-[#E284C1]">Python</span>
                    <span className="text-[#FDB8E7]">25%</span>
                  </div>
                  <div className="w-full bg-[#0d1117] rounded-full h-2">
                    <div className="bg-[#A5586E] h-2 rounded-full" style={{width: '25%'}}></div>
                  </div>
                </div>
              </div>
            </div>

            <div className="bg-[#161b22] rounded-lg p-6 border border-[#30363d] hover:border-[#C85C9D] transition-colors">
              <h3 className="text-lg font-semibold text-[#FDB8E7] mb-4">Trophies</h3>
              <div className="grid grid-cols-4 gap-3">
                {['🏆', '⭐', '🎯', '💎', '🔥', '⚡', '🚀', '✨'].map((trophy, idx) => (
                  <div key={idx} className="text-4xl text-center hover:scale-110 transition-transform cursor-pointer">
                    {trophy}
                  </div>
                ))}
              </div>
            </div>
          </div>
        </div>

        {/* Contribution Graph Mock */}
        <div className="bg-[#161b22] rounded-lg p-6 border border-[#30363d] mb-12">
          <h3 className="text-lg font-semibold text-[#FDB8E7] mb-4">Contribution Graph</h3>
          <div className="grid grid-cols-52 gap-1">
            {Array.from({ length: 364 }).map((_, idx) => (
              <div 
                key={idx} 
                className="w-3 h-3 rounded-sm hover:scale-110 transition-transform cursor-pointer"
                style={{
                  backgroundColor: Math.random() > 0.7 ? 
                    (Math.random() > 0.5 ? '#C85C9D' : '#A5586E') : 
                    (Math.random() > 0.3 ? '#8A5568' : '#30363d')
                }}
              />
            ))}
          </div>
        </div>

        {/* Neon Divider */}
        <div className="w-full h-1 bg-gradient-to-r from-[#A5586E] via-[#FDB8E7] to-[#A5586E] rounded-full mb-12 shadow-[0_0_20px_rgba(253,184,231,0.5)]"></div>

        {/* Current Projects */}
        <div className="mb-12">
          <h2 className="text-3xl font-bold text-[#FDB8E7] mb-8 text-center">🔥 Current Projects</h2>
          <div className="grid md:grid-cols-2 gap-6">
            {[1, 2].map((project) => (
              <div key={project} className="bg-[#161b22] rounded-lg p-6 border border-[#30363d] hover:border-[#C85C9D] transition-all hover:scale-105 cursor-pointer">
                <div className="flex items-start justify-between mb-3">
                  <h3 className="text-xl font-bold text-[#FDB8E7]">Project Name {project}</h3>
                  <span className="text-[#C85C9D]">⭐ 42</span>
                </div>
                <p className="text-[#E284C1] mb-4">
                  An awesome project description that explains what this project does and why it's amazing.
                </p>
                <div className="flex gap-2">
                  <span className="text-xs bg-[#C85C9D] text-white px-3 py-1 rounded-full">React</span>
                  <span className="text-xs bg-[#A5586E] text-white px-3 py-1 rounded-full">TypeScript</span>
                </div>
              </div>
            ))}
          </div>
        </div>

        {/* Neon Divider */}
        <div className="w-full h-1 bg-gradient-to-r from-[#A5586E] via-[#FDB8E7] to-[#A5586E] rounded-full mb-12 shadow-[0_0_20px_rgba(253,184,231,0.5)]"></div>

        {/* Activity Section */}
        <div className="bg-[#161b22] rounded-lg p-8 border border-[#30363d] mb-12">
          <h2 className="text-3xl font-bold text-[#FDB8E7] mb-6 text-center">🎯 What I'm up to</h2>
          <pre className="bg-[#0d1117] p-6 rounded-lg text-sm overflow-x-auto border border-[#30363d] mb-6">
            <code className="text-[#E284C1]">
{`interface CurrentActivity {
  learning: string[];
  working_on: string[];
  collaboration: string;
  fun_fact: string;
}

const myActivity: CurrentActivity = {
  learning: ["AI/ML", "Web3", "Cloud Architecture"],
  working_on: ["Full-stack applications", "Open source contributions"],
  collaboration: "I'm looking to collaborate on innovative projects",
  fun_fact: "I can debug code faster than I can debug my life 🤷‍♂️"
};`}
            </code>
          </pre>

          <div className="space-y-3">
            <div className="flex items-start gap-3">
              <span className="text-2xl">🔭</span>
              <p className="text-[#E284C1]">Currently working on <span className="text-[#FDB8E7] font-semibold">cutting-edge web applications</span></p>
            </div>
            <div className="flex items-start gap-3">
              <span className="text-2xl">🌱</span>
              <p className="text-[#E284C1]">Learning <span className="text-[#FDB8E7] font-semibold">AI/ML and blockchain technologies</span></p>
            </div>
            <div className="flex items-start gap-3">
              <span className="text-2xl">👯</span>
              <p className="text-[#E284C1]">Open to collaborate on <span className="text-[#FDB8E7] font-semibold">open source projects</span></p>
            </div>
            <div className="flex items-start gap-3">
              <span className="text-2xl">💬</span>
              <p className="text-[#E284C1]">Ask me about <span className="text-[#FDB8E7] font-semibold">React, Node.js, TypeScript</span></p>
            </div>
            <div className="flex items-start gap-3">
              <span className="text-2xl">⚡</span>
              <p className="text-[#E284C1]">Fun fact: <span className="text-[#FDB8E7] font-semibold">Coffee powers my code</span> ☕</p>
            </div>
          </div>
        </div>

        {/* Neon Divider */}
        <div className="w-full h-1 bg-gradient-to-r from-[#A5586E] via-[#FDB8E7] to-[#A5586E] rounded-full mb-12 shadow-[0_0_20px_rgba(253,184,231,0.5)]"></div>

        {/* Quote Section */}
        <div className="bg-[#161b22] rounded-lg p-8 border border-[#C85C9D] mb-12 text-center">
          <h2 className="text-2xl font-bold text-[#FDB8E7] mb-4">💭 Dev Quote</h2>
          <blockquote className="text-xl text-[#E284C1] italic mb-3">
            "Code is like humor. When you have to explain it, it's bad."
          </blockquote>
          <p className="text-[#FDB8E7]">– Cory House</p>
        </div>

        {/* Neon Divider */}
        <div className="w-full h-1 bg-gradient-to-r from-[#A5586E] via-[#FDB8E7] to-[#A5586E] rounded-full mb-12 shadow-[0_0_20px_rgba(253,184,231,0.5)]"></div>

        {/* Support Section */}
        <div className="text-center mb-12">
          <h2 className="text-3xl font-bold text-[#FDB8E7] mb-4">💖 Support My Work</h2>
          <p className="text-[#E284C1] mb-6">If you like my work, consider supporting me:</p>
          <a href="#" className="inline-flex items-center gap-2 bg-[#FDB8E7] hover:bg-[#E284C1] transition-colors px-8 py-4 rounded-lg font-bold text-[#1a1a1a] text-lg">
            <Coffee size={24} />
            Buy Me a Coffee
          </a>
        </div>

        {/* Footer */}
        <div className="text-center py-8">
          <p className="text-xl text-[#E284C1] italic mb-4">
            ✨ "Code is like humor. When you have to explain it, it's bad." – Cory House
          </p>
          <p className="text-[#FDB8E7] mb-6">Made with 💖 and lots of ☕ by <span className="font-bold">YOUR NAME</span></p>
        </div>
      </div>

      {/* Footer Wave */}
      <div className="w-full h-[120px] bg-gradient-to-r from-[#A5586E] via-[#C85C9D] to-[#E284C1] relative overflow-hidden">
        <div className="absolute inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPjxkZWZzPjxwYXR0ZXJuIGlkPSJncmlkIiB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHBhdHRlcm5Vbml0cz0idXNlclNwYWNlT25Vc2UiPjxwYXRoIGQ9Ik0gNDAgMCBMIDAgMCAwIDQwIiBmaWxsPSJub25lIiBzdHJva2U9InJnYmEoMjU1LDI1NSwyNTUsMC4xKSIgc3Ryb2tlLXdpZHRoPSIxIi8+PC9wYXR0ZXJuPjwvZGVmcz48cmVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSJ1cmwoI2dyaWQpIi8+PC9zdmc+')] opacity-30"></div>
      </div>
    </div>
  );
}
