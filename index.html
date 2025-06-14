"use client"

import { Button } from "@/components/ui/button"
import { Card, CardContent, CardDescription, CardHeader, CardTitle } from "@/components/ui/card"
import { Badge } from "@/components/ui/badge"
import { Download, Shield, Zap, Globe, Star, Users, Github, ExternalLink } from "lucide-react"
import { useState, useEffect } from "react"

export default function HomePage() {
  const [activeUsers, setActiveUsers] = useState(0)
  const [githubStars, setGithubStars] = useState(0)
  const [hasVisited, setHasVisited] = useState(false)

  useEffect(() => {
    // Check if user has visited before
    const visited = localStorage.getItem("anker-visited")
    if (!visited) {
      // New user - increment active users
      const currentUsers = Number.parseInt(localStorage.getItem("anker-active-users") || "0")
      const newUserCount = currentUsers + 1
      localStorage.setItem("anker-active-users", newUserCount.toString())
      localStorage.setItem("anker-visited", "true")
      setActiveUsers(newUserCount)
      setHasVisited(false)
    } else {
      // Returning user
      const currentUsers = Number.parseInt(localStorage.getItem("anker-active-users") || "0")
      setActiveUsers(currentUsers)
      setHasVisited(true)
    }

    // Fetch GitHub stars
    fetchGitHubStats()
  }, [])

  const fetchGitHubStats = async () => {
    try {
      const response = await fetch("https://api.github.com/repos/AMSdel/Anker-Browser")
      const data = await response.json()
      setGithubStars(data.stargazers_count || 0)
    } catch (error) {
      console.error("Failed to fetch GitHub stats:", error)
    }
  }

  const handleStarProject = () => {
    window.open("https://github.com/AMSdel/Anker-Browser", "_blank")
  }

  const handleDownload = () => {
    window.open("https://github.com/AMSdel/Anker-Browser/releases/latest", "_blank")
  }

  return (
    <div className="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100">
      {/* Header */}
      <header className="container mx-auto px-4 py-6">
        <nav className="flex items-center justify-between">
          <div className="flex items-center space-x-2">
            <div className="w-8 h-8 bg-blue-600 rounded-lg flex items-center justify-center">
              <Globe className="w-5 h-5 text-white" />
            </div>
            <span className="text-2xl font-bold text-gray-900">Anker Browser</span>
          </div>
          <div className="hidden md:flex items-center space-x-6">
            <a href="#features" className="text-gray-600 hover:text-gray-900">
              Features
            </a>
            <a href="#download" className="text-gray-600 hover:text-gray-900">
              Download
            </a>
            <Button variant="outline" size="sm" onClick={handleStarProject} className="flex items-center space-x-2">
              <Github className="w-4 h-4" />
              <span>GitHub</span>
              <Badge variant="secondary">{githubStars}</Badge>
            </Button>
          </div>
        </nav>
      </header>

      {/* Hero Section */}
      <section className="container mx-auto px-4 py-16 text-center">
        <div className="flex justify-center space-x-4 mb-4">
          <Badge variant="secondary" className="flex items-center space-x-1">
            <Users className="w-3 h-3" />
            <span>{activeUsers} Active Users</span>
          </Badge>
          <Badge variant="outline" className="flex items-center space-x-1">
            <Star className="w-3 h-3" />
            <span>{githubStars} GitHub Stars</span>
          </Badge>
        </div>

        {!hasVisited && (
          <div className="bg-green-100 border border-green-400 text-green-700 px-4 py-3 rounded mb-6 max-w-md mx-auto">
            Welcome! You're our newest user #{activeUsers}
          </div>
        )}

        <h1 className="text-5xl md:text-6xl font-bold text-gray-900 mb-6">
          Browse the web with
          <span className="text-blue-600"> Anker</span>
        </h1>
        <p className="text-xl text-gray-600 mb-8 max-w-2xl mx-auto">
          A modern, fast, and secure browser built for Windows. Experience the web like never before with cutting-edge
          technology and privacy-first design.
        </p>

        {/* Download Section */}
        <div className="flex flex-col sm:flex-row gap-4 justify-center mb-8" id="download">
          <Button size="lg" className="bg-blue-600 hover:bg-blue-700 text-white px-8 py-3" onClick={handleDownload}>
            <Download className="w-5 h-5 mr-2" />
            Download for Windows
          </Button>
          <Button size="lg" variant="outline" className="px-8 py-3" onClick={handleStarProject}>
            <Github className="w-5 h-5 mr-2" />
            View on GitHub
          </Button>
        </div>

        <p className="text-sm text-gray-500 mb-12">
          Currently available for Windows • Version 1.0 • Free & Open Source
        </p>

        {/* Browser Mockup */}
        <div className="max-w-4xl mx-auto">
          <div className="bg-white rounded-lg shadow-2xl p-4">
            <div className="flex items-center space-x-2 mb-4">
              <div className="w-3 h-3 bg-red-500 rounded-full"></div>
              <div className="w-3 h-3 bg-yellow-500 rounded-full"></div>
              <div className="w-3 h-3 bg-green-500 rounded-full"></div>
              <div className="flex-1 bg-gray-100 rounded-md px-4 py-2 ml-4">
                <span className="text-gray-500">https://github.com/AMSdel/Anker-Browser</span>
              </div>
            </div>
            <div className="bg-gray-50 rounded-md h-64 flex items-center justify-center">
              <div className="text-center">
                <Globe className="w-16 h-16 text-blue-600 mx-auto mb-4" />
                <p className="text-gray-600 font-semibold">Anker Browser</p>
                <p className="text-gray-500 text-sm">Fast • Secure • Private</p>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* Features Section */}
      <section className="container mx-auto px-4 py-16" id="features">
        <div className="text-center mb-12">
          <h2 className="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Why Choose Anker Browser?</h2>
          <p className="text-xl text-gray-600 max-w-2xl mx-auto">
            Built with modern web standards and user privacy in mind
          </p>
        </div>

        <div className="grid md:grid-cols-3 gap-8">
          <Card>
            <CardHeader>
              <Zap className="w-12 h-12 text-blue-600 mb-4" />
              <CardTitle>Lightning Fast</CardTitle>
              <CardDescription>
                Optimized for Windows with native performance and minimal resource usage
              </CardDescription>
            </CardHeader>
          </Card>

          <Card>
            <CardHeader>
              <Shield className="w-12 h-12 text-green-600 mb-4" />
              <CardTitle>Privacy First</CardTitle>
              <CardDescription>
                Built-in privacy protection with no tracking and secure browsing by default
              </CardDescription>
            </CardHeader>
          </Card>

          <Card>
            <CardHeader>
              <Github className="w-12 h-12 text-purple-600 mb-4" />
              <CardTitle>Open Source</CardTitle>
              <CardDescription>
                Fully open source and transparent. Community-driven development on GitHub
              </CardDescription>
            </CardHeader>
          </Card>
        </div>
      </section>

      {/* GitHub Integration Section */}
      <section className="bg-white py-16">
        <div className="container mx-auto px-4 text-center">
          <h2 className="text-3xl font-bold text-gray-900 mb-8">Open Source & Community Driven</h2>
          <div className="max-w-2xl mx-auto">
            <Card>
              <CardContent className="pt-6">
                <div className="flex items-center justify-center space-x-8 mb-6">
                  <div className="text-center">
                    <div className="text-3xl font-bold text-blue-600">{githubStars}</div>
                    <div className="text-gray-600">GitHub Stars</div>
                  </div>
                  <div className="text-center">
                    <div className="text-3xl font-bold text-green-600">{activeUsers}</div>
                    <div className="text-gray-600">Active Users</div>
                  </div>
                  <div className="text-center">
                    <div className="text-3xl font-bold text-purple-600">1</div>
                    <div className="text-gray-600">Latest Release</div>
                  </div>
                </div>
                <p className="text-gray-600 mb-6">
                  Anker Browser is completely open source. Star the project on GitHub to show your support and stay
                  updated with the latest releases.
                </p>
                <div className="flex flex-col sm:flex-row gap-4 justify-center">
                  <Button onClick={handleStarProject} className="flex items-center space-x-2">
                    <Star className="w-4 h-4" />
                    <span>Star on GitHub</span>
                  </Button>
                  <Button variant="outline" onClick={handleDownload} className="flex items-center space-x-2">
                    <ExternalLink className="w-4 h-4" />
                    <span>View Releases</span>
                  </Button>
                </div>
              </CardContent>
            </Card>
          </div>
        </div>
      </section>

      {/* Download CTA */}
      <section className="bg-blue-600 py-16">
        <div className="container mx-auto px-4 text-center">
          <h2 className="text-3xl md:text-4xl font-bold text-white mb-4">Ready to Try Anker Browser?</h2>
          <p className="text-xl text-blue-100 mb-8 max-w-2xl mx-auto">
            Download the latest version for Windows and experience faster, more secure browsing
          </p>
          <div className="flex flex-col sm:flex-row gap-4 justify-center">
            <Button size="lg" variant="secondary" className="px-8 py-3" onClick={handleDownload}>
              <Download className="w-5 h-5 mr-2" />
              Download Latest Release
            </Button>
            <Button
              size="lg"
              variant="outline"
              className="border-white text-white hover:bg-white hover:text-blue-600 px-8 py-3"
              onClick={handleStarProject}
            >
              <Github className="w-5 h-5 mr-2" />
              View Source Code
            </Button>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gray-900 text-white py-12">
        <div className="container mx-auto px-4">
          <div className="grid md:grid-cols-4 gap-8">
            <div>
              <div className="flex items-center space-x-2 mb-4">
                <div className="w-8 h-8 bg-blue-600 rounded-lg flex items-center justify-center">
                  <Globe className="w-5 h-5 text-white" />
                </div>
                <span className="text-xl font-bold">Anker Browser</span>
              </div>
              <p className="text-gray-400">Fast, secure, and private browsing for Windows.</p>
            </div>
            <div>
              <h3 className="font-semibold mb-4">Download</h3>
              <ul className="space-y-2 text-gray-400">
                <li>
                  <button onClick={handleDownload} className="hover:text-white">
                    Windows (Latest)
                  </button>
                </li>
                <li>
                  <button onClick={handleDownload} className="hover:text-white">
                    Release Notes
                  </button>
                </li>
              </ul>
            </div>
            <div>
              <h3 className="font-semibold mb-4">Community</h3>
              <ul className="space-y-2 text-gray-400">
                <li>
                  <button onClick={handleStarProject} className="hover:text-white">
                    GitHub Repository
                  </button>
                </li>
                <li>
                  <button onClick={handleStarProject} className="hover:text-white">
                    Report Issues
                  </button>
                </li>
              </ul>
            </div>
            <div>
              <h3 className="font-semibold mb-4">Stats</h3>
              <ul className="space-y-2 text-gray-400">
                <li>Active Users: {activeUsers}</li>
                <li>GitHub Stars: {githubStars}</li>
                <li>Platform: Windows</li>
              </ul>
            </div>
          </div>
          <div className="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
            <p>&copy; 2024 Anker Browser. Open source project by AMSdel.</p>
          </div>
        </div>
      </footer>
    </div>
  )
}
