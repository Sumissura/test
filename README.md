greeting: [
'Welcome to Sumissura!',
'How can we help you today?',
{
type: 'choose' 'I\'d like to know more about',
answers: [{
'text': 'Your Fabrics,
'path': 'fabrics'
},
{
'text': 'How it Works',
'path': 'howitworks'
{
'text': 'Contact Customer Service',
'path': 'customerservice'
}
{
'text': 'The Measuring Process',
'path': 'measuringprocess'
}
}]
}
],
'howitworks': [
'Sumissura believes a unique wardrobe should be accessible to everyone.',
'Our mission is simple: to give people the freedom to choose their own style and reveal their personality through their outfit.',
'Every day. At an affordable price.',
{
type: 'choose',
answers: [{
'text': 'tell me more about the measuring process.',
'path': 'measuringprocess'
},
{
'text': 'I\d like to contact customer service',
'path': 'customerservice'
}]
}
],
'contact': [
'We\'d love to hear from you!',
'Email us at <a href="mailto:cs@sumissura.com">cs@sumissura.com</a>',
 ],
