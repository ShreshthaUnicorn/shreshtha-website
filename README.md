# shreshtha-website
// Netlify Function: turns text into a natural AI voice using ElevenLabs. // Keys live in Netlify environment variables, never in the website code. exports.handler = async (event) => {   if (event.httpMethod !== "POST") return { statusCode: 405, body: "POST only" };   let b;   
