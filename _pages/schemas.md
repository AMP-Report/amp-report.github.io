---
layout: default
title: Database Schemas
description: Explore our comprehensive database schema options for the AMP Report platform
permalink: /schemas/
---

<section class="schema-navigation">
    <div class="container section">
        <h2>🏗️ Database Schema Development Options</h2>
        <p>Explore our different database architecture approaches designed to support scalability, performance, and future growth. Each option represents a different balance of complexity, features, and implementation strategy.</p>
        
        <div class="schema-options">
            <div class="schema-option">
                <h4>📊 Schema Option A</h4>
                <p>Comprehensive multi-tenant architecture with advanced features including portfolio management, collaboration tools, and extensive analytics capabilities.</p>
                <a href="{{ '/database-schema-diagram-option-a.html' | relative_url }}" class="schema-link">View Schema A</a>
            </div>
            
            <div class="schema-option">
                <h4>🔒 Schema Option B</h4>
                <p>Immutable, geo-intelligent database design focused on data integrity, temporal tracking, and scalable cost analysis with 15+ core tables.</p>
                <a href="{{ '/database-schema-diagram-option-b.html' | relative_url }}" class="schema-link">View Schema B</a>
            </div>
            
            <div class="schema-option">
                <h4>🏆 Schema Option C</h4>
                <p>Simplified, performance-optimized design for rapid development and deployment. Perfect for MVP and early-stage development.</p>
                <a href="{{ '/database-schema-diagram-option-c.html' | relative_url }}" class="schema-link">View Schema C</a>
            </div>
            
            <div class="schema-option" style="border: 2px solid rgba(255, 255, 255, 0.5); background: rgba(255, 255, 255, 0.15);">
                <h4>🚀 Schema Option C (Merged)</h4>
                <p><strong>RECOMMENDED:</strong> Ultimate synthesis combining Option A's comprehensive features with Option B's immutability and geographic intelligence. Features 40+ tables across 9 business domains.</p>
                <a href="{{ '/database-schema-diagram-option-c-merged.html' | relative_url }}" class="schema-link" style="background: rgba(255, 255, 255, 0.3); border: 2px solid rgba(255, 255, 255, 0.5);">View Merged Schema</a>
            </div>
        </div>

        <div style="margin-top: 3rem; padding: 2rem; background: rgba(255, 255, 255, 0.1); border-radius: 15px;">
            <h3>🔐 Critical Success Factors</h3>
            <div class="features-grid" style="margin-top: 1rem;">
                <div style="color: white;">
                    <h5>Data Integrity</h5>
                    <p>Normalized structure prevents inconsistencies with cascade rules and immutable report snapshots</p>
                </div>
                <div style="color: white;">
                    <h5>Performance at Scale</h5>
                    <p>Indexed foreign keys, denormalized report data, and separated read/write operations</p>
                </div>
                <div style="color: white;">
                    <h5>Future Flexibility</h5>
                    <p>JSON fields for extensible metadata, modular design, and calculation templates</p>
                </div>
                <div style="color: white;">
                    <h5>Multi-Tenant Ready</h5>
                    <p>Row-level security, shared cost data with tenant-specific calculations</p>
                </div>
            </div>
        </div>
    </div>
</section> 