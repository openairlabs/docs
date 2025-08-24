---
title: "Internal: Documentation Restructure Plan"
hidden: true
robots: "noindex, nofollow"
---

# 📋 Flyweel Documentation Restructure Plan

## 🎯 Overview
This plan reorganizes the existing MD files into a logical documentation structure while adding depth to the existing content **WITHOUT inventing new features**. Focus is on enhancing what exists in the current beta.

## 📁 Current Assets Analysis
**Existing MD Files to Enhance:**
- `quickstart.md` - Getting started guide (needs conversion to .mdx + depth)
- `adgrid.md` - Campaign management hub (solid content, needs enhancement)
- `ai-agent.md` - AI chat assistant (good examples, needs more depth)
- `integrations.md` - Platform connections (Google/Meta only, needs expansion)
- `reports.md` - Analytics dashboard (basic, needs more detail)
- `settings.md` - Account management (covers basics, needs depth)

**Current Mintlify Structure Issues:**
- Generic "essentials" and "ai-tools" don't match Flyweel's actual product
- Placeholder API docs that should be realistic for beta stage
- Missing organization around actual Flyweel features

## 🏗️ New Documentation Structure (Beta-Appropriate)

### **Tab 1: User Guide**
*Covers the actual features available in Flyweel's beta*

#### **📚 Getting Started**
1. **Welcome to Flyweel** (`index.mdx` - ✅ Already updated)
2. **Quick Start Guide** (`quickstart.mdx` - Convert from `quickstart.md` + add depth)

#### **🔗 Platform Connections**  
3. **Connecting Ad Platforms** (`integrations.mdx` - Enhanced from `integrations.md`)

#### **📊 Core Features**
4. **AdGrid - Campaign Manager** (`features/adgrid.mdx` - Enhanced from `adgrid.md`)
5. **AI Assistant** (`features/ai-agent.mdx` - Enhanced from `ai-agent.md`)
6. **Reports Dashboard** (`features/reports.mdx` - Enhanced from `reports.md`)

#### **⚙️ Account & Settings**
7. **Settings & Account** (`settings.mdx` - Enhanced from `settings.md`)

### **Tab 2: API Reference**
*Basic API docs appropriate for beta stage*

#### **🔌 API Basics**
8. **API Introduction** (`api-reference/introduction.mdx` - Keep existing but enhance)
9. **API Examples** (`api-reference/examples.mdx` - Convert existing endpoint examples)

## 🚀 Implementation Strategy

### **Phase 1: Core Structure (Priority 1)**
1. ✅ Update navigation structure in `docs.json`
2. Convert existing `.md` files to `.mdx`
3. Create folder structure: `features`, `integrations`, `settings`
4. Move files to their respective folders

### **Phase 2: Content Enhancement (Priority 2)**  
1. **Add depth to existing content with:**
   - More detailed step-by-step instructions (e.g., in `quickstart.mdx`)
   - Add screenshots and visual guides (placeholders for now)
   - **Troubleshooting sections** in `integrations.mdx` and `quickstart.mdx`
   - **Best practices** in `adgrid.mdx` and `reports.mdx`
   - **Common use cases** in `ai-agent.mdx`

### **Phase 3: Polish & Integration (Priority 3)**
1. Add code examples for API reference
2. Create interactive elements (e.g., tooltips, callouts)
3. Add cross-references and related articles between docs
4. Ensure all internal links are updated and working

## 📝 Content Enhancement Guidelines

### **Existing Files Enhancement:**
- **Preserve core information** - Don't remove working content
- **Add context** - Explain why features matter for SpendOps
- **Include examples** - Real-world scenarios for ad teams
- **Add troubleshooting** - Common issues and solutions
- **Cross-reference** - Link related features together

### **New Content Focus:**
- **SpendOps methodology** - How Flyweel eliminates waste
- **Platform-specific guidance** - Google vs Meta vs TikTok best practices  
- **Team workflows** - How advertising teams can collaborate
- **ROI optimization** - Concrete steps to improve performance
- **Integration patterns** - How Flyweel fits into existing workflows

## 🎨 Visual & UX Improvements

### **Page Structure:**
- Consistent headers with clear hierarchy
- Progressive disclosure (overview → details)
- Action-oriented CTAs
- Related articles suggestions

### **Content Types:**
- **Guides** - Step-by-step instructions
- **References** - Quick lookups and parameters
- **Tutorials** - Complete workflows  
- **Best Practices** - Optimization recommendations

## 📊 Success Metrics
- **Coverage** - All major Flyweel features documented
- **Depth** - Each page provides actionable guidance
- **Navigation** - Users can find information in ≤3 clicks
- **Consistency** - Uniform structure and tone
- **Completeness** - No broken links or missing references

This plan transforms generic documentation into a comprehensive SpendOps platform guide that serves both new users and power users while maintaining the existing valuable content.
